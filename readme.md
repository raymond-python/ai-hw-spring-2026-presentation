# AI Spring 2026 Final Project

## Overview

This project summarizes my work from AI Spring 2026. The goal was to explore both the performance and robustness of neural networks using the MNIST handwritten digit dataset.

The work consists of two connected projects:

1. MNIST Image Recognition Neural Network
2. Adversarial Attacks on MNIST

---

## Project 1: MNIST Image Recognition Neural Network

Repository:

https://github.com/raymond-python/ai-hw-spring-2026-nn

### Description

Implemented and compared three neural network architectures for handwritten digit classification:

- Multi-Layer Perceptron (MLP)
- Convolutional Neural Network (CNN)
- Transformer Encoder

### Topics Covered

- Image Classification
- Deep Learning
- Data Augmentation
- Model Evaluation

### Technologies

- Python
- PyTorch
- Torchvision

---

## Project 2: Adversarial Attacks on MNIST

Repository:

https://github.com/raymond-python/ai-hw-spring-2026-aa

### Description

Evaluated the robustness of a CNN model against adversarial attacks.

### Attack Methods

- FGSM
- I-FGSM / PGD
- Momentum I-FGSM

### Results

| Attack | Recognition Rate Before Attack | Attack Success Rate |
|----------|----------|----------|
| FGSM | 98.91% | 81.40% |
| I-FGSM / PGD | 98.91% | 99.99% |
| Momentum I-FGSM | 98.91% | 99.86% |

### Topics Covered

- Adversarial Machine Learning
- AI Security
- Model Robustness
- Gradient-Based Attacks

---

## Project Relationship

The adversarial attack project builds upon the image classification project.

The first project focused on creating accurate neural network models, while the second project examined how vulnerable those models are to adversarial perturbations.

Together, these projects demonstrate both the strengths and limitations of modern deep learning systems.

---
