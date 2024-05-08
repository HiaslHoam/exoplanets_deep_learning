# Results: Baseline CNN

<div class="grid grid-cols-2 justify-center justify-items-center items-start">

<div class="opacity-100">
<img src="/images/results/cnn/best_perf_historie.png" class="max-h-95 shadow-lg"/>
<p class="text-gray-500 font-italic text-sm">
Training history for the basic CNN stopped after 85 epochs. To avoid overfitting the training is being stopped as soon as the validation loss is increasing over a set number of epochs.
</p>
</div>
<div class="grid grid-cols-2 gap-2 ml-4 opacity-100">
<div>
<img src="/images/results/cnn/best_perf_test.png" class="max-h-40 shadow-lg"/>
<div class="text-gray-500 font-italic text-xs mt-3">
Predictions on the test set
</div>
</div>
<div>
<img src="/images/results/cnn/best_perf_test_hist.png" class="max-h-39.5 shadow-lg"/>
<div class="text-gray-500 font-italic text-xs mt-3">
Histogram of the predictions on the test set
</div>
</div>
<div>
<img src="/images/results/cnn/best_perf_train.png" class="max-h-40 shadow-lg"/>
<div class="text-gray-500 font-italic text-xs mt-3">
Predictions on the training set
</div>
</div>
<div>
<img src="/images/results/cnn/best_perf_train_hist.png" class="max-h-39.5 shadow-lg"/>
<div class="text-gray-500 font-italic text-xs mt-3">
Histogram of the predictions on the training set
</div>
</div>
</div>
</div>

<div class="min-w-30 position-absolute top-62 left-41 bg-red-500 p-2 rounded-xl bg-opacity-40 shadow-xl max-w-85 backdrop-blur-sm z-10">
Now we don't have overfitting anymore and the predictions on the training set are similar in accuracy to the test set.
</div>
<img class="min-w-30 position-absolute top-80 left-121 rotate-220 opacity-70" src="https://upload.wikimedia.org/wikipedia/commons/5/57/Short_left_arrow_-_red.svg" />
<img class="min-w-30 position-absolute top-53 left-121 rotate-140 opacity-70" src="https://upload.wikimedia.org/wikipedia/commons/5/57/Short_left_arrow_-_red.svg" />