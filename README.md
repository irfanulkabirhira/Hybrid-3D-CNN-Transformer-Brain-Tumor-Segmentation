# Hybrid 3D CNN + Transformer for Brain Tumor Segmentation

This project implements a **hybrid deep learning framework for brain tumor segmentation** using multi-modal MRI data from the **BraTS dataset**.  
The model combines **3D Convolutional Neural Networks, Attention mechanisms, and Transformer-based global context learning** to improve segmentation accuracy.

---

## Project Overview

Medical image segmentation plays a crucial role in:

- Computer-aided diagnosis
- Treatment planning
- Tumor monitoring

This project proposes a **Hybrid CNN-Transformer architecture** designed to improve:

- Tumor boundary detection
- Global feature learning
- Multi-modal MRI fusion

---

## Dataset

Dataset used: **BraTS 2021**

MRI Modalities:

- T1
- T1ce
- T2
- FLAIR

Dataset preprocessing includes:

- Tumor-rich slice extraction
- Multi-modal alignment
- Patch-based volumetric input

Final dataset used for experiments:

- **377 patients**
- **10 tumor slices per patient**



---

## Proposed Framework

BraTS Dataset
↓
10 Slice Extraction
↓
377 Patients
↓
Dataset Loader
↓
Hybrid Model
(CNN + Attention + Transformer)
↓
Hybrid Loss
↓
Training Loop
↓
Evaluation Metrics
↓
Segmentation Visualization




---

## Model Architecture

The architecture consists of:

- **3D CNN Encoder** for spatial feature extraction
- **Attention Fusion Module** to enhance tumor regions
- **Transformer Bottleneck** for global context learning
- **Decoder Network** with skip connections
- **Multi-class segmentation output**

Input Shape:


MRI Modalities:

- T1
- T1ce
- T2
- FLAIR

---

## Loss Function

Hybrid loss function combining:

- Cross Entropy Loss
- Dice Loss
- Boundary-aware loss

This improves segmentation accuracy and boundary precision.

---

## Evaluation Metrics

The model is evaluated using:

- Dice Similarity Coefficient
- Intersection over Union (IoU)
- Precision
- Recall
- F1 Score
- Hausdorff Distance
- Expected Calibration Error

Example results:

| Metric | Score |
|------|------|
Dice | 0.81 |
IoU | 0.69 |
Precision | 0.82 |
Recall | 0.82 |
F1 Score | 0.81 |

---

## Example Segmentation Results

The model predicts tumor regions from MRI scans:


