---
title: VAE with Inverse Autoregressive flows
summary: Replicated "VAE with Inverse Autoregressive Flow" paper by Kingma et al. 
weight: 2
tags:
- Machine_Learning
date: "2016-04-27T00:00:00Z"

image:
  placement: 1
  focal_point: "Center"
  preview_only: true
share: false

links:
- icon: file-pdf
  icon_pack: fas
  name: report
  url: https://drive.google.com/file/d/1hrkyaF80q8nEUjVId0QEZbVq9iU1roOK/view?usp=sharing


---

This report replicates the work of "Improving Variational Inference with Inverse Autoregressive Flow" to improve the accuracy of Generative models. VAEs introduce a parametric Inference model to approximate the true latent posterior and optimize the parameters using an Evidence Lower Bound objective function. The follow-up work improves this by increasing the flexibility of the Inference model through Nonlinear Autoregressive Transforms called Normalizing Flow. This can lead to a tighter lower bound and higher accuracy of the Generative model. The report will replicate experiments on MNIST and CIFAR-10 datasets using standard-VAEs, simple IAF-VAE, and bidirectional ResNet VAE with PixelCNN masking.

