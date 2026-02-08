---
title: "Interpretable Deep Learning for GI Endoscopic Images"
date: 2026-01-13
description: "Enhanced multi-class classification of gastrointestinal endoscopic images using EfficientNetB3 and LIME."
tags: ["Deep Learning", "Medical AI", "Interpretability", "Research"]
link: "https://doi.org/10.1088/2057-1976/ae2b72"
---

## 📄 Abstract

Gastrointestinal (GI) endoscopy serves as a vital tool for assessing the GI tract and diagnosing related disorders. Recent progress in deep learning has shown significant improvements in identifying anomalies using sophisticated models and data augmentation strategies.

This study introduces an enhanced approach to improve classification accuracy using **8,000 labeled endoscopic images** from the Kvasir dataset, categorized into eight distinct classes. Leveraging **EfficientNetB3** as the backbone, our proposed architecture eliminates the reliance on data augmentation while maintaining moderate model complexity.

### 🚀 Key Results
- **Test Accuracy**: 94.25%
- **Precision**: 94.29%
- **Recall**: 94.24%

### 🧠 Interpretability & Usability
Furthermore, **Local Interpretable Model-agnostic Explanation (LIME)** saliency maps are employed to enhance interpretability by highlighting critical regions in the images that influence model predictions.

To facilitate real-world usability, a user-friendly interface was developed using **Gradio**, enabling users to:
1. Upload images
2. Generate predictions
3. View confidence levels
4. Maintain a history of past results

**Citation**: Astitva Kamble et al 2026 Biomed. Phys. Eng. Express 12 015043
**DOI**: [10.1088/2057-1976/ae2b72](https://doi.org/10.1088/2057-1976/ae2b72)
