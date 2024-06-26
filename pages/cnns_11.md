---
title: Convolutional Neural Networks
---

# Convolutional Neural Networks

Putting it all together

<div class="grid grid-cols-5 justify-center justify-items-center items-start mt-18 ml-35">

<Transform scale="0.33" class="col-span-1 min-w-100 bg-red-200 p-8 shadow-xl">
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

<img src="/images/2DConvolved.jpg" class="max-h-90 min-h-40 shadow-xl" />
</div>
</div>
</Transform>

<div class="col-span-1 -ml-55 mt-2 p-3 shadow-xl">
<img class="max-w-26" src="/images/relu.png" />
</div>

<Transform scale="0.33" class="col-span-1 ml-100 mt-8 bg-blue-200 p-8 shadow-xl">
<div class="grid grid-rows-2 justify-center justify-items-center items-start">
<div class="row-span-1 self-center">

$$
\begin{gather*}
\begin{bmatrix}
\color{green} 50 & \color{blue} 100\\
\color{red} 166 & \color{orange} 24 
\end{bmatrix}
\overset{\text{avg pooling}}{\longleftarrow}
\begin{bmatrix}
\color{green} 163 & \color{green} 17 & \color{blue} 179 & \color{blue} 123\\
\color{green} 0 & \color{green} 21 & \color{blue} 89 & \color{blue} 10 \\
\color{red} 173 & \color{red} 196 & \color{orange} 9 & \color{orange} 15 \\
\color{red} 175 & \color{red} 118 & \color{orange} 62 & \color{orange} 12
\end{bmatrix}
\overset{\text{max pooling}}{\longrightarrow}
\begin{bmatrix}
\color{green} 163 & \color{blue} 179\\
\color{red} 196 & \color{orange} 62 
\end{bmatrix}
\end{gather*}
$$

</div>
<div class="row-span-1 self-center">
<div class="grid grid-cols-3 grid-flow-col gap-25">
<div class="col-span-1"><img class="max-h-90 min-h-40 shadow-xl" src="/images/avg_pooling.png"/></div>
<div class="col-span-1"><img class="max-h-90 min-h-40 shadow-xl" src="/images/2DConvolved.jpg"/></div>
<div class="col-span-1"><img class="max-h-90 min-h-40 shadow-xl" src="/images/max_pooling.png"/></div>
</div>
</div>
</div>

</Transform>




<div class="col-span-1 ml-44 min-w-50 mt-9.7 p-1 shadow-xl">
<img src="/images/nn.png" />
</div>



<mdi-plus-circle-outline class="position-absolute left-52 top-68"/>
<mdi-plus-circle-outline class="position-absolute left-97 top-68"/>
<mdi-plus-circle-outline class="position-absolute left-166.5 top-68"/>
<mdi-plus-circle-outline class="position-absolute left-52 top-68"/>
</div>




<style>

  .list li{
    margin-bottom: 1.8rem !important;
  }
</style>

<!--
Building blocks out of the first three layers and repeat them
-->
