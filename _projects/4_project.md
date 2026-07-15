---
layout: page
title: Disentangled VAE for Disordered Speech Assessment
description: Multimodal β-VAE for intelligibility assessment of healthy, MCI, and dementia speech.
importance: 4
category: research
related_publications: true
---

**May 2025 · Speech AI · Multimodal learning · PyTorch**

Designed a multimodal disentangled β-VAE for classifying healthy, mild cognitive impairment (MCI), and dementia speech using audio spectrograms and BERT text embeddings on the ICASSP 2025 Alzheimer's detection dataset.

### Problem

Disordered speech assessment requires models that capture both acoustic and linguistic cues while remaining interpretable enough for clinical analysis.

### Approach

- Combined STFT spectrogram encoders with BERT text embeddings in a disentangled β-VAE framework
- Used triplet loss and total correlation loss to encourage separable latent representations
- Built fragmentation, augmentation, and fusion pipelines for robust multimodal training

### Results

- Produced linearly separable latent clusters across speech disorder classes
- Outperformed baseline models in validation accuracy and interpretability
- Manuscript under review at the *International Journal of Pattern Recognition and Artificial Intelligence*

### Tech stack

PyTorch, β-VAE, BERT, STFT features, multimodal fusion, representation learning
