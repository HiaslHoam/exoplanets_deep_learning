---
title: Training Results
---

# Training Results

Performance Metrics

<div class="grid grid-cols-2 justify-items-center">
<div class="col-span-1">
<img src="/images/pre_rec.png" class="p-4 shadow-xl max-w-90"/>
</div>
<div class="col-span-1 grid items-center">

* They first compare the deep model to other models made by the authors: ***linear*** and ***fully connected***

<div>

* **Precision**: is the fraction of classified planets that are actually planets

    * Precision $= \frac{TP}{TP+FP}$

* **Recall**: is the fraction of true planets that are actually classified as such (also called True Positive Rate)
    * Recall $= \frac{TP}{TP+FN}$

</div>
</div>
</div>

<style>
.not-active {
  opacity: 20%;
}
</style>

<!--
Precision: What percentage of **positive** cases is correct?
Recall: What percentage of the **relevant** cases is correct?

**Relevant** here means the planets we want to find while **positive** is just all the positively classified planets
-->
