# Results: Baseline CNN

<div class="grid grid-cols-2 justify-center justify-items-center items-start">

<div class="opacity-40">
<img src="/images/results/cnn/hist_overf.png" class="max-h-95 shadow-lg"/>
<p class="text-gray-500 font-italic text-sm">
Training history for the basic CNN over 4000 epochs
</p>
</div>
<div class="grid grid-cols-2 gap-2 ml-4 opacity-100">
<div>
<img src="/images/results/cnn/overf_test_set.png" class="max-h-40 shadow-lg"/>
<div class="text-gray-500 font-italic text-xs mt-3">
Predictions on the test set
</div>
</div>
<div>
<img src="/images/results/cnn/overf_test_set_hist.png" class="max-h-39.5 shadow-lg"/>
<div class="text-gray-500 font-italic text-xs mt-3">
Histogram of the predictions on the test set
</div>
</div>
<div>
<img src="/images/results/cnn/overf_test_trainset.png" class="max-h-40 shadow-lg"/>
<div class="text-gray-500 font-italic text-xs mt-3">
Predictions on the training set
</div>
</div>
<div>
<img src="/images/results/cnn/overf_train_set_hist.png" class="max-h-39.5 shadow-lg"/>
<div class="text-gray-500 font-italic text-xs mt-3">
Histogram of the predictions on the training set
</div>
</div>
</div>


</div>
<div class="min-w-30 position-absolute top-32 left-90 bg-red-500 p-2 rounded-xl bg-opacity-40 shadow-xl max-w-85 backdrop-blur-sm">
This is called overfitting and should normally be avoided. <br/> <br/>
However, it shows that the model should technically be able to learn certain features from the input images.
</div>
<img class="min-w-30 position-absolute top-80 left-132 rotate-220 opacity-70" src="https://upload.wikimedia.org/wikipedia/commons/5/57/Short_left_arrow_-_red.svg" />