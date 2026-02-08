---
title: "SmolWhisper — Lightweight Multilingual ASR"
date: 2024-06-01
draft: false
description: "A high-efficiency Whisper-Tiny (30M) ASR model for multilingual speech recognition"
tags: ["Deep Learning", "ASR", "PyTorch", "HuggingFace"]
weight: 1
---

## Overview

SmolWhisper is a lightweight yet powerful Automatic Speech Recognition (ASR) model built on top of the Whisper architecture. Designed for efficiency without sacrificing accuracy, it's perfect for resource-constrained environments.

## 🔧 Tech Stack

- **PyTorch** - Deep learning framework
- **HuggingFace Transformers** - Model architecture and tokenization
- **FlashAttention** - Optimized attention mechanism
- **DDP (Distributed Data Parallel)** - Multi-GPU training
- **WGAN** - Data augmentation

## ✨ Key Features

### High-Efficiency Training
- Trained on **250+ hours** of GigaSpeech dataset
- Multi-GPU **Distributed Data Parallel (DDP)** for scalable training
- **35% faster convergence** compared to baseline

### Advanced Optimization
- **FlashAttention** integration for memory-efficient attention
- **bfloat16 precision** training for reduced compute overhead
- **WGAN-based data augmentation** for enhanced training stability

### Production Ready
- Scalable pipelines for **multilingual speech recognition**
- **Noise-robust transcription** capabilities
- Lightweight model size (**30M parameters**) suitable for edge deployment

## 📊 Results

| Metric | Performance |
|--------|-------------|
| Model Size | 30M parameters |
| Training Data | 250+ hrs GigaSpeech |
| Convergence Speed | 35% faster |
| Precision | bfloat16 |

## 🔗 Links

- [GitHub Repository](https://github.com/kushagra8881)
