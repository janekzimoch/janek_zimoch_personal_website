---
title: Causal Inference
summary: Built a generative model for a causal inference problem with some latent variables.  
weight: 1
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
  name: raport
  url: https://drive.google.com/file/d/1nk6uNk9OEz_AIB0ryFuKjtfXdt5eVFtR/view
- icon: github
  icon_pack: fab
  name: github
  url: https://github.com/janekzimoch/Causal_Inference_with_Probabilistic_Modelling/blob/main/L48Project.ipynb

---

Probabilistic modelling is a framework for understanding and inferring probability distributions while handling uncertainty in a principled way. It was initially developed to answer questions of an associative nature and has been argued in recent years that it is not equipped to deal with problems of a causal nature. The reason is that there can often be lurking confounders which can lead to counter-intuitive results. In this report, we aim to understand how to conduct causal inference and answer counterfactual questions using probabilistic models. In this paper we focus on conducting causal inference using probabilistic modelling, specifically using Bayesian Networks. We will define a set of conditional independence assumptions which can then be used to factorize a joint distribution over all variables of interest. We will then define some further assumptions that relate distributions in the observational and counterfactual worlds, which is necessary to allow for use of observational data in causal inference. We will then define an appropriate probabilistic model that represents the data generating process and learn the model parameters from the training set. Finally, we can infer the posterior distributions over the variables in the counterfactual world using the rules of probability.

