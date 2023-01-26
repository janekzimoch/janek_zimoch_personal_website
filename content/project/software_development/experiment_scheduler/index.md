---
title: Experiment scheduler
summary: Program for scheduling many smaller experiments on GPU in sequence.  
weight: 1
tags:
- Software_Development
date: "2016-04-27T00:00:00Z"

# image:
#   placement: 1
#   focal_point: "Center"
#   preview_only: true
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

Experiments in machine learning often take between few minutes to couple of hours. Often you it's hard to predict how long the next experiment will ran for, and you might find yourself checking every couple of minutes if it has finished or not, such that you can start running the next experiment. I found this process of manual experiment scheduling time consuming and frustrating, which kept distracting me from carrying out other work. 

I created this program to ran all experiments from a single main.py script. All experiment would be loaded to a queue and would be offloaded for training on GPU depending on GPU memory utilisation (i.e. we would train as many experiments in parallel as the memory allows, other experiments would wait for their turn.)

Next extension (for futrue work) is to develop a notification system (i.e. via whatsapp or email) to get notifications as experiments finish training or fail executing. 
