# DL-CNN-Architectures-AlexNet-VGG
This lab focuses on implementing and comparing two widely known CNN architectures: AlexNet and VGG. The goal of the experiment is to understand how architectural depth, convolutional layer sizes, and parameter count affect model performance on a binary image classification task. 

# CNN Architectures — AlexNet & VGG

This repository contains implementations of **AlexNet** and **VGG** architectures using TensorFlow/Keras for **binary image classification**.

---

## 📌 Project Overview

| Model | Key Features | Purpose |
|-------|--------------|---------|
| AlexNet | Deep CNN with ReLU & Dropout | Earlier CNN innovation |
| VGG16/VGG19 | Small receptive fields, deep layers | Feature extraction comparison |

The goal is to compare the performance between these architectures on the same dataset.

---

## 📚 Dataset
Used a custom **binary image dataset** loaded with `ImageDataGenerator`.


> You can replace it with **any binary classification dataset**.

---

## 🏗 Model Training Details

| Setting | Value |
|--------|------|
| Optimizer | Adam |
| Loss function | Binary Crossentropy |
| Metrics | Accuracy |
| Train/Val split | via ImageDataGenerator |

---

## 📊 Results

| Model | Accuracy | Observation |
|-------|----------|-------------|
| AlexNet | 85.71%  | Likely lower due to simpler architecture |
| VGG | 76.47% | Better representation learning |

## 1. AlexNet

## ✅ Accuracy: 85.71%

##Strengths: Strong feature extraction, works well on real-world images, reliable performance.

##Limitations: Heavy model, requires more resources compared to simple CNNs.

##2. CNN (Custom)

##✅ Accuracy: 78.43%

##Strengths: Lightweight, faster to train, good for small and medium-scale image tasks.

##Limitations: Struggles with complex image features, not as powerful as deeper models.

##3. VGG

##✅ Accuracy: 76.47%

##Strengths: Deep network, captures fine details, good theoretical performance.

##Limitations: Very slow, high memory requirement, less practical without strong hardware.

##Conclusion: AlexNet performs best here for real-world recognition, CNN is a good balance for smaller tasks, while VGG, though detailed, is less efficient.

---


## Requirements

tensorflow
matplotlib
numpy
opencv-python

