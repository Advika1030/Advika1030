---
layout: page
title: Sketch-to-Face Image Translation using DCGAN
description: Deep learning pipeline converting face sketches to realistic images on the CUHK dataset.
importance: 3
category: research
github: Advika1030/ReFaceIt
github_stars: true
---

**Jun 2025 · Generative AI · DCGAN · Computer vision**

Created a deep learning pipeline using DCGANs to translate face sketches into realistic facial images on the CUHK Face Sketch FERET dataset.

### Problem

Sketch-to-photo translation is an ill-posed image generation task requiring the model to hallucinate realistic texture and identity cues from sparse line drawings.

### Approach

- Trained two DCGAN variants with different reconstruction objectives
- Compared Binary Cross Entropy loss against Mean Squared Error loss
- Built a modular codebase with training logs, checkpoints, and organized outputs

### Results

| Loss function | SSIM |
| ------------- | ---- |
| BCE           | 0.51 |
| MSE           | 0.55 |

### Tech stack

PyTorch, DCGAN, CUHK dataset, image generation, training visualization

**Repository:** [Advika1030/ReFaceIt](https://github.com/Advika1030/ReFaceIt)
