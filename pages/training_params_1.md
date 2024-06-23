# Training

Training Parameters for the best model

<div class="grid grid-cols-5 justify-center justify-items-center items-start">
    <Transform scale="0.67" class="col-span-3 justify-center items-center ml-50 mt-20">
          <div class="list p-3 shadow-xl">

|    **Parameter**   | Batch Size | Epochs | Optimizer | Learning Rate $\alpha$ | Decay Rates $\beta_{1,2}$ | $\epsilon$ | Dropout | Loss Function |
|-------|------------|--------|-----------|------------------------|---------------------|------------------|--|----|
| **Value** | 64         | 50     | Adam      | $10^{-5}$                  | 0.9 , 0.999                 | $10^{-8}$| Only on FC layers | Cross Entropy |

  </div>
  </Transform>
  <Transform scale="0.9" class="list col-span-2">
  <div>

  * Google Vizier used for parameter optimization

  <p class="not-active">


  * Small batch size allows a more efficient computation
  * Few epochs of training can avoid overfitting
  * Adam is a common optimizer, allowing a more efficient training
  * Surprising to me to see such a small learning rate with just 50 epochs

  </p>
  
  </div>
  </Transform>
</div>


<style>

  .list li{
    margin-bottom: 1rem !important;
  }
  .not-active {
    opacity: 20%;
  }
</style>