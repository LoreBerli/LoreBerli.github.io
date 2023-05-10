---
layout: post
title:  "Identity Crisis: Memorization and Generalization under Extreme Overparameterization - ICRL2020"
date:   2021-02-04 10:13:32 +0100
categories: [papers, theory, overparameterization]
---


## What is _inductive_ or _learning_ bias?
In a machine learning model *inductive bias* refers to the set of assumptions affecting  
## How to study it?
In this paper a framework to better analyze inductive bias is presented.
Starting from the observation that *modern deep NNs* are largely **overparameterized**.

Predictions in the vicinity of the training samples are regularized by continuity or smoothness constraints, while predictions further away from training samples determine **generalizations** performances.
The different behaviors reflect the learning bias of the model and the learning algorithm.


<div class="row">
  <div class="col-4">{% include figure.html path="assets/img/identity.jpg" class="img-fluid rounded z-depth-1" %}</div>
  <div class="col">Predictions in the vicinity of the training samples are regularized by continuity or smoothness constraints, while predictions further away from training samples determine **generalizations** performances.
The different behaviors reflect the learning bias of the model and the learning algorithm.</div>

</div>


In order to better understand this behavior the authors use two approaches:
* Learning with one example
  - Extreme overparameterization
  - Easy to determine distance from the training example


* Learning the identity map $$f(x)=x$$
  - Requires all input features to be transmitted to the output
  - Affords detailed analysis of visualization and model behaviour


---
Find the paper here! [ICLR2020](https://iclr.cc/virtual_2020/poster_B1l6y0VFPr.html).
