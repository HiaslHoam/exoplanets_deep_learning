# How was this done before?

Coughlin et al. (2016)


<div class="grid grid-cols-3 justify-center justify-items-center items-start">
<div class="col-span-2 self-center ml-80">
<Transform :scale="0.65">
  <PlotlyGraph filePath="plots/test.json" graphWidth="900"/>
</Transform>
</div>
<div class="list ml-5">

* Decision tree to classify planet candidates (PCs)
* Similar to manual selection
* Many steps necessary to classify a PC
* Multiple different trees for different problems

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