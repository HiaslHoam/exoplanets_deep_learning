# Results: EfficientNet-B7

<div class="grid grid-cols-2 justify-center justify-items-center items-start">

<div class="opacity-100">
<img src="/images/results/efficient/eff_history.png" class="max-h-95 shadow-lg"/>
<p class="text-gray-500 font-italic text-sm">
Training history for EfficientNet-B7 after 4000 epochs
</p>
</div>
<div class="grid grid-cols-2 gap-2 ml-4 opacity-100">
<div>
<img src="/images/results/efficient/test_EfficientNetB7_scatter.png" class="max-h-40 shadow-lg"/>
<div class="text-gray-500 font-italic text-xs mt-3">
Predictions on the test set
</div>
</div>
<div>
<img src="/images/results/efficient/test_EfficientNetB7_hist.png" class="max-h-39.5 shadow-lg"/>
<div class="text-gray-500 font-italic text-xs mt-3">
Histogram of the predictions on the test set
</div>
</div>
<div>
<img src="/images/results/efficient/training_EfficientNetB7_scatter.png" class="max-h-40 shadow-lg"/>
<div class="text-gray-500 font-italic text-xs mt-3">
Predictions on the training set
</div>
</div>
<div>
<img src="/images/results/efficient/training_EfficientNetB7_hist.png" class="max-h-39.5 shadow-lg"/>
<div class="text-gray-500 font-italic text-xs mt-3">
Histogram of the predictions on the training set
</div>
</div>
</div>
</div>

<div class="min-w-30 position-absolute top-46 left-90 bg-red-500 p-2 rounded-xl bg-opacity-40 shadow-xl max-w-85 backdrop-blur-xl">
Despite the low training loss, EfficientNet has similar problems as VGG. Especially with smaller galaxy clusters it struggles to predict accurately.
</div>
<img class="min-w-30 position-absolute top-80 left-132 rotate-220 opacity-70" src="https://upload.wikimedia.org/wikipedia/commons/5/57/Short_left_arrow_-_red.svg" />