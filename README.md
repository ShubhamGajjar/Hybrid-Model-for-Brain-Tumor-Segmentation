# Brain Tumor Segmentation Using VGG16 U-Net Variants

This repository contains various deep learning models for brain tumor segmentation, leveraging the power of VGG16-based U-Net architectures. The project includes implementations of:

- VGG16 U-Net
- VGG16 Attention U-Net
- VGG16 Scaler Attention U-Net
- VGG16 MCA U-Net

## Table of Contents
- [Introduction](#introduction)
- [Models](#models)
- [Architecture](#Architecture)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributions](#contributions)
- [License](#license)

## Introduction
This project aims to provide accurate brain tumor segmentation using advanced U-Net architectures. By leveraging VGG16 as the encoder backbone, these models achieve high performance in medical image segmentation tasks.

## Models
The repository contains implementations of the following models:
- `VGG16_U-Net`: Standard U-Net with VGG16 encoder.
- `VGG16_Attention_U-Net`: U-Net with attention mechanism added to the VGG16 encoder.
- `VGG16_Scaler_Attention_U-Net`: U-Net with scaler attention blocks.
- `VGG16_MCA_U-Net`: U-Net with multi-scale channel attention.
## Architecture
![Architecture](https://github.com/ShubhamGajjar/Hybrid-Model-for-Brain-Tumor-Segmentation/assets/66659212/45269eb7-73e2-41e4-8999-afb98a75dfc4)


## Dataset
The models were trained and evaluated on a comprehensive dataset of brain MRI images. We have created our own dataset combining it with different sources and based on that we have achieved our Results.
[Link of Dataset](https://www.kaggle.com/datasets/shubhamgajjar/brain-tumor-classification-2d)

## Installation
Clone the repository and install the required dependencies:
```bash
git clone https://github.com/ShubhamGajjar/Hybrid-Model-for-Brain-Tumor-Segmentation.git
cd BrainTumorSegmentation
pip install -r requirements.txt
```
## Results
![Model_results](https://github.com/ShubhamGajjar/Hybrid-Model-for-Brain-Tumor-Segmentation/assets/66659212/3bf6371e-47c4-4b6d-b243-23fb7da07d34)

## Contributions
- [`ShubhamGajjar`](https://github.com/ShubhamGajjar): Model development, integration of preprocessing and visualizations.
- [`DeepJoshi10`](https://github.com/DeepJoshi10): Collaboration on preprocessing and dataset preparation.
- [`avi-poptani-003`](https://github.com/avi-poptani-003): Collaboration on visualizations and analyzing results.
