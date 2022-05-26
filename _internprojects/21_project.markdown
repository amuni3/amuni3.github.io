---
layout: page
title: Fast Adaptation of Recurrent Neural Networks
description: NNAISENSE
img: /project_pics/RNN.png
---

We introduce a transfer learning approach which enables fast and efficient adaptation of 
Recurrent Neural Network models. A nominal RNN model is first identified using available
measurements. The system dynamics are then assumed to change, leading to an
unacceptable degradation of the nominal model performance on the perturbed system.

To cope with the mismatch, the model is augmented with an additive correction term trained
on fresh data from the new dynamic regime. The correction term is learned through a 
Bayesian Linear Regression (BLR) method defined in terms of the features spanned by the
nominal model's Jacobian with respect to its parameters.

<div class="img_poster">
	<img class="col three" src="{{ site.baseurl }}/project_pics/RNN_adaptation.png" atl="RNN Adaptation">
</div>

<div class="img_poster">
	<img class="col three"
	 src="{{ site.baseurl }}/project_pics/RNN_initialization.png" atl="RNN Initialization">
</div>

A non-parametric view of the approach is also proposed, which extends the recent 
work on Gaussian Process with Neural Tangent Kernel (NTK-GP) to
the RNN case (RNTK-GP). Finally, we introduce an approach to initialize the RNN
state based on a context of past data, so that an estimate of the initial state
is not needed on top of the parameter estimation. 

The code for this project is available on
<a href="https://github.com/forgi86/RNN-adaptation"><b>GitHub</b></a>.

<a href="https://arxiv.org/pdf/2201.08660.pdf"><b>Publication</b></a>:\\
[1]  &nbsp; M. Forgione, <b>A. Muni</b>, D. Piga, and M. Gallieri.
On the adaptation of recurrent neural networks for system identification, 2022.
 Preprint: <i>arXiv:2201.08660</i>. (<u>Under Review</u>)