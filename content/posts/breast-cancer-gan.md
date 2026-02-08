---
title: "Data Augmentation for Breast Cancer Imaging using GANs"
date: 2026-02-08
description: "Generative Adversarial Networks for small breast cancer imaging datasets (Ongoing)."
tags: ["GANs", "Medical AI", "Data Augmentation", "Research", "Ongoing"]
---

> **Status**: Ongoing Research

## 📄 Abstract

The limited availability of annotated medical imaging data remains a critical barrier in developing robust deep learning models, particularly in breast Ultrasound (US). This study presents a novel conditional **Generative Adversarial Network (GAN)** framework tailored for synthesizing high-quality breast US images in data-constrained environments.

### 🔬 Methodology
Our method is evaluated on **100 US images** (one of the smallest publicly available breast US datasets) from the Open Access Series of Breast US Dataset (OASBUD), simulating real-world clinical scarcity. By generating standardized B-mode images directly from raw radio-frequency (RF) data, our framework minimizes inter-vendor variability and produces diagnostically coherent images.

**Architecture**:
- Progressive Growing GAN + StyleGAN
- Spectral Normalization
- Residual Connections
- Pearson correlation-based loss function

### 📊 Preliminary Results
- **Classification Accuracy**: 82%
- **F1-Score**: 0.83 (Benign & Malignant)
- **Segmentation Dice Score**: 0.74

### 📥 Download Paper
The full paper is available for download below:

[📄 **Download Full Paper (PDF)**](/papers/breast-cancer-gan.pdf)

*(Note: Please ensure the file `breast-cancer-gan.pdf` is uploaded to the static/papers/ directory)*
