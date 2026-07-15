---
layout: page
title: Medical Image Inpainting for Brain MRI
description: Diffusion-based inpainting with DDPM and Diffusion KAN (U-KAN) for tumor-masked T1 MRI slices.
importance: 1
category: research
github: https://github.com/Advika1030/wavelet-inpainting
---

**Nov 2025 · Medical imaging · Diffusion models · PyTorch**

Implemented and compared diffusion-based models to restore healthy tissue in tumor-masked T1 MRI slices, benchmarking a DDPM baseline against a Diffusion KAN model with a U-KAN backbone.

### Problem

Brain MRI inpainting requires reconstructing anatomically plausible tissue in regions masked by tumors, where standard CNN backbones can struggle with complex nonlinear structure.

### Approach

- Built DDPM and Diffusion KAN pipelines for tumor-masked T1 slice restoration
- Used KAN layers to model nonlinear anatomical structure more flexibly than conventional convolutions
- Applied RePaint-style denoising to improve sample quality during inference

### Results

| Metric | Diffusion KAN |
| ------ | ------------- |
| PSNR   | 20.06         |
| SSIM   | 0.80          |
| MSE    | 0.012         |

### Tech stack

PyTorch, diffusion models, DDPM, U-KAN, RePaint, medical image preprocessing

**Repository:** [Advika1030/wavelet-inpainting](https://github.com/Advika1030/wavelet-inpainting)