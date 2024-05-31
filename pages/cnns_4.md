# What is a Convolution?

2D-Convolutions

<div class="grid grid-cols-6 justify-center justify-items-center items-start">
<div class="col-span-3 self-center">
  <img src="/images/eye_array.png" class="max-h-90 shadow-xl" />
</div>
<div class="col-span-2 self-center">

<div class="grid grid-rows-2 items-center justify-items-center">

<div>

$g = \begin{bmatrix}
  0 & -1 & 0\\
  -1 & 4 & -1 \\
  0 & -1 & 0
\end{bmatrix}$

</div>

<img src="/images/2DConvolved.jpg" class="max-h-90 min-h-40 shadow-xl not-active" />
</div>
</div>
<div class="col-span-1 self-center">

<div>

* Kernel for edge detection
* Compares a pixel to its four direct neighbours

</div>

<div class="mt-5 not-active">

* Resulting image might be easier for feature detection

</div>


</div>
</div>

<style>

  .list li{
    margin-bottom: 1.8rem !important;
  }
    .not-active {
    opacity: 20%;
}
</style>