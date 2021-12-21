---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 5

title: Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: Research Intern
    company: Toshiba Research Europe
    # company_url: ''
    # company_logo: org-gc
    location: 3 months, Cambridge, UK
    date_start: '2021-11-01'
    date_end: '2022-02-01'
    description: |2-
      * **Project objective:** Reformulate surface normal regression in CNN based photometric-stereo task, as a conditional density estimation task using flexible Conditional Normalising Flows.
      * **Motivation:** Conditional density estimation allows to regress entire posterior distribution rather than just its mean, as is the case in a deterministic formulation of regression tasks. Access to the full posterior distribution can improve quality of 3D surface integration by leveraging the full posterior distribution during inference. This will improve state of the art of a few light CNN based photometric stereo, where mapping from input to output may sometimes become ambigious due to shadows, color saturation, self-reflections and other ocmplex light-surface interactions.
      * **Technology used:** Python, Synthetic data generation in C++, PyTorch, Pyro, Conditional Normalising Flows, Graphics and Rendering theory.


        
  - title: Graduate Student Researcher
    company: University of Cambridge
    location: 5 months for thesis + 2 months full time after graduation, Cambridge, UK
    date_start: '2021-04-01'
    date_end: '2021-11-01'
    description: |2-
      * **Thesis title:** “Multimodal Scene Coordinate Regression: A Novel, Probabilistic Approach to Camera Re-Localisation in Ambiguous Environments”
      * **Motivation:** In visual Localisation (the task of regressing 6-DoF camera pose from an RGB image), the mapping from input to output can often be multimodal, due to structure, symmetry, and texturless surfaces in the environment. During my research, I extended the scene coordinate regression approach from unimodal to multimodal setting, to enable reasoning in such ambigious settings.
      * **Main Results:** My model multimodal framework achieved 48% reduction in position error as compared to the same network, but with unimodal output head, when tested in a large indoor environment (James Dyson Building, Cambridge University Engineering Department).
      * **Deliverables:** My framework consists of two parts: (1) multimodal scene coordiante prediction network and (2) Multimodal inference for 6-DoF camera pose. The mulitmodal scene coordiante prediction is based on my adaptation of Mixture Density Network with a Winner-Takes-All learning strategy. For the inference i built Factor Graph model of relationship between variables and applied Belief Propagation algorithm to arrive at a marginal distribution over 6-DoF camera pose.
      * **Technology used:** Python, TensorFlow, Keras, Feature Pyramid Network, Mixture Density Network, Winner-Takes-All learning strategy, Factor Graph, Belief Propagation.

  - title: Data Science Intern
    company: DeepSense.ai
    location: 3 months, Warsaw, PL
    date_start: '2019-06-01'
    date_end: '2019-09-01'
    description: |2-
        * 
        * Achieved 48% reduction in position error as compared to the same network, but with unimodal output head.
        * TensorFlow, Feature Pyramid Network, Mixture Density Network, Factor Graph, Belief Propagation,  
design:
  columns: '2'
---
