---
title: Convolutional Neural Networks
---

# Convolutional Neural Networks

Pooling

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

<style>

  .list li{
    margin-bottom: 1.8rem !important;
  }
</style>

<!--
WAIT WITH EXPLANATION FOR NEXT SLIDE
-->
