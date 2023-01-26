---
title: Visual Localisation
summary: Developing novel, probabilistic approach to multimodal visual localisation.  
weight: 1
tags:
- Computer_Vision
date: "2016-04-27T00:00:00Z"

image:
  placement: 1
  focal_point: "Center"
  preview_only: true
share: false

links:
- icon: file-pdf
  icon_pack: fas
  name: thesis
  url: https://drive.google.com/file/u/1/d/1OssLvysJ5aUTim_fFeum1bbjGFs-lpnu/view?usp=sharing
- icon: github
  icon_pack: fab
  name: github
  url: https://github.com/janekzimoch/localisation_with_image

---

The aim of camera relocalization is to predict a 6-degree of freedom camera pose from a 2D image input. Current state-of-the-art methods can achieve centimeter-level accuracy. However, most methods only predict a single pose estimate, which is not sufficient for ambiguous images. In this thesis, we propose a novel probabilistic framework for multimodal scene coordinate regression (M-SCR) which uses a per-pixel adaptation of Mixture Density Network and factor graph and belief propagation to infer the 6-DoF posterior distribution over camera pose, which outperforms unimodal approaches on multiple datasets. To the best of our knowledge, this is the first work to do multimodal camera relocalization using scene coordinate regression.

