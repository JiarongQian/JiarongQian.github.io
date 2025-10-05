---
title: "Large-Scale Models for Medical Image Quality Control "
collection: research
permalink: /research/2024-01-01-your-research-project
date: 2025-10-05
---
## Project Objective: 
Develop a multimodal medical imaging quality control model that automatically assesses the acquisition quality of multi-site human images and supports clinical diagnosis, particularly assisting doctors with limited reading experience in resource-constrained region


## Main Output
Lung CT Artifact Quality Control
○	Cleaned and annotated 500+ clinical 3D CT datasets and established a standardized preprocessing pipeline.
○	Built a 3D U-Net pipeline for lung CT motion artifact segmentation with 85% DICE performance (50 cases).
○	Fine-tuned ResNet18/50 for artifact classification (lung/muscle/artifact layers) with precision over 90%.
○	Achieved 90%+ ROC-AUC rates using ResNet (2D) and 80%+ Recall using ResNet(3D).

 Knee X-ray Image Segmentation
○	Preprocessed data through normalization, scaling, data augmentation, and data partitioning.
○	Developed a 2D U-Net model to achieve 92% DICE in knee joint space segmentation on 3000+ slices.

## 项目截图
![项目截图](/images/research-screenshot.png)

## 架构图
![系统架构图](/images/system-architecture.png)

## 实验结果
![实验结果对比](/images/experiment-results.png)

## 相关链接
- [论文链接](您的论文链接)
- [代码仓库](您的代码链接)
- [演示视频](您的演示链接)
