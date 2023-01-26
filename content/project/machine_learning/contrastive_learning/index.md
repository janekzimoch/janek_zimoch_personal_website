---
title: Deep Metric Learning
summary: Used Contrastive learning to classify whether two query images are of the same class. 
weight: 3
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
  url: https://drive.google.com/file/d/1006MqMKfQyFElBgYatTc38KA1aQbhHs3/view
- icon: github
  icon_pack: fab
  name: github
  url: https://github.com/janekzimoch/Deep_Metric_Learning

---

In the image matching task, a model receives a pair of images and determines if they are similar or not. We use Deep Distance Metric Learning to extract a lower dimensional representation of images and measure their similarity. The goal is to cluster similar images in a K-dimensional space. Two main sub-problems are identifying an objective function and designing a CNN feature extractor. We evaluate different approaches and CNN architectures in this method. Our training procedure and techniques to speed up convergence are also presented and evaluated.

