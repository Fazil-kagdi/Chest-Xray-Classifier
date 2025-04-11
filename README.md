# Chest-Xray-Pneumonia-Classifier
A deep learning model built with PyTorch to classify chest X-ray images into normal or diseased categories using a pretrained ResNet18 architecture. Trained on a labeled dataset of chest X-rays for automated medical diagnosis support.

## 🔍 Overview

This project uses ResNet-18 to detect pneumonia from chest X-ray images. Both a scratch-trained and a pretrained version of the model were evaluated.

---

## 🧠 Model Performance

| Model              | Overall Accuracy | Normal Accuracy | Pneumonia Accuracy |
|--------------------|------------------|------------------|---------------------|
| ResNet-Scratch     | 86.38%           | 70.51%           | 95.90%              |
| ResNet-Pretrained  | **90.87%**       | **85.04%**       | **94.36%**          |

> ✅ The pretrained model significantly improved classification of **normal** cases while maintaining high pneumonia accuracy.

