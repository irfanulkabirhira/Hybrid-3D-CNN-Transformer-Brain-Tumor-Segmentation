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
