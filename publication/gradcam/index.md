---
title: "Grad-CAM: Visual Explanations from Deep Networks via Gradient-based Localization"
authors:
- Ramprasaath R. Selvaraju
- Michael Cogswell
- Abhishek Das
- Ramakrishna Vedantam
- Devi Parikh
- Dhruv Batra
date: "2017-10-01"
publication: "ICCV"
publication_types: ["1"]
abstract: "We propose a technique for producing \"visual explanations\" for decisions from a large class of CNN-based models, making them more transparent. Our approach - Gradient-weighted Class Activation Mapping (Grad-CAM), uses the gradients of any target concept, flowing into the final convolutional layer to produce a coarse localization map highlighting important regions in the image for predicting the concept. Grad-CAM is applicable to a wide variety of CNN model-families: (1) CNNs with fully-connected layers, (2) CNNs used for structured outputs, (3) CNNs used in tasks with multimodal inputs or reinforcement learning, without any architectural changes or re-training. We apply Grad-CAM to off-the-shelf image classification, captioning, and visual question answering (VQA) models, including ResNet-based architectures. In the context of image classification models, our visualizations (a) lend insights into their failure modes, (b) are robust to adversarial images, (c) outperform previous methods on localization, (d) are more faithful to the underlying model and (e) help achieve generalization by identifying dataset bias. For captioning and VQA, we show that even non-attention based models can localize inputs. Finally, we design and conduct human studies to measure if Grad-CAM helps users establish appropriate trust in predictions from models and show that Grad-CAM helps untrained users successfully discern a 'stronger' model from a 'weaker' one even when both make identical predictions."
featured: true
image:
  filename: gradcam_teaser1
  focal_point: Smart
  preview_only: false
links:
- name: arXiv
  url: https://arxiv.org/abs/1610.02391
- name: Blog
  url: https://mlatgt.blog/2018/09/05/choose-your-neuron-incorporating-domain-knowledge-through-neuron-importance/
- name: Code
  url: https://github.com/ramprs/grad-cam
- name: Demo
  url: http://gradcam.cloudcv.org/
--- 