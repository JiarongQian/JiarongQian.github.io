---
title: "	ToothFussion: Generate a completed tooth from crown information"
collection: research
permalink: /research/2024-01-01-your-research-project
date: 2025-10-05
---

## Project Objective: 
To generate complete CBCT tooth structures from partial IOS crown information and textual descriptions, thereby reducing dental patients’ exposure to CT radiation and lowering the risk of radiation-induced malignancies.

## Main Output:
○	Trained an IOS segmentation model on over 3,000 patient OBJ files (accuracy >97%) and successfully applied it to 145 new patient cases to obtain high-quality segmented data;
○	Performed full-mouth registration of CBCT/IOS STL files using CloudCompare and the ICP algorithm, computed and applied transformation matrices to individual teeth, and constructed CBCT/IOS single-tooth registration pairs;
○	Fine-tuned a VQ-VAE 3D latent compression model on 2,000+ single-tooth datasets to better adapt it for tooth morphology modeling;
○	In Progress: Training a multimodal diffusion model (3D data + text conditions) with GPT and 3D U-Net as the primary architectures, aiming to generate complete tooth shapes from partial crown geometries.


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
