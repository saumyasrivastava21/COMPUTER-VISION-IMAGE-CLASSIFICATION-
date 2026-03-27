🧠 Deep Learning Image Classification — Complete Research & Tutorial Hub

A research-driven Computer Vision tutorial repository covering the full evolution of Image Classification architectures — from early Convolutional Neural Networks to modern Transformer-based vision models.

This repository is designed to help learners understand research papers → implement architectures → run experiments → visualize model behaviour → prepare for real-world deployment.

🚀 Learning Objective

This project focuses on:

✅ architectural intuition
✅ research paper understanding
✅ implementation from scratch
✅ transfer learning pipelines
✅ interpretability tools
✅ production optimization

It serves as a complete deep learning architecture learning journey.

📚 Architectures Covered
🟢 LeNet — Foundation of CNN

📄 Paper:
🔗 http://yann.lecun.com/exdb/publis/pdf/lecun-98.pdf

Authors: Yann LeCun et al.

What You Learn
Convolution + pooling basics
Early digit recognition systems
Feature extraction intuition

Tutorial includes:

✔ MNIST training pipeline
✔ Feature map visualization
✔ Performance benchmarking

🔵 AlexNet — Deep Learning Breakthrough

📄 Paper:
🔗 https://papers.nips.cc/paper/4824-imagenet-classification-with-deep-convolutional-neural-networks.pdf

Authors: Alex Krizhevsky, Ilya Sutskever, Geoffrey Hinton

What You Learn
ReLU activation revolution
Dropout regularization
GPU training impact

Tutorial includes:

✔ Full architecture coding
✔ Experiment vs shallow CNN
✔ Accuracy comparison

🟣 VGG16 / VGG19 — Depth Scaling

📄 Paper:
🔗 https://arxiv.org/pdf/1409.1556.pdf

Authors: Karen Simonyan, Andrew Zisserman

What You Learn
Deep stacked convolution
Feature hierarchy
Parameter explosion trade-off

Tutorial includes:

✔ Transfer learning
✔ Grad-CAM visualization
✔ Training time vs accuracy analysis

🟡 GoogLeNet / Inception — Multi-Scale Learning

📄 Paper:
🔗 https://arxiv.org/pdf/1409.4842.pdf

Authors: Christian Szegedy et al.

What You Learn
Inception modules
Multi-branch convolution
Dimensionality reduction

Tutorial includes:

✔ Inception block implementation
✔ Auxiliary classifier training
✔ Parameter efficiency comparison

🔴 DenseNet — Feature Reuse Revolution

📄 Paper:
🔗 https://arxiv.org/pdf/1608.06993.pdf

Authors: Gao Huang et al.

What You Learn
Dense connectivity
Improved gradient flow
Feature reuse

Tutorial includes:

✔ Dense block coding
✔ Memory vs performance experiment

🟠 MobileNet — Edge AI Architecture

📄 Paper:
🔗 https://arxiv.org/pdf/1704.04861.pdf

Authors: Andrew G. Howard et al.

What You Learn
Depthwise separable convolution
Latency vs accuracy
Edge deployment

Tutorial includes:

✔ Lightweight benchmarking
✔ Parameter reduction study

🟢 EfficientNet — Compound Scaling

📄 Paper:
🔗 https://arxiv.org/pdf/1905.11946.pdf

Authors: Mingxing Tan, Quoc Le

What You Learn
Width vs depth vs resolution scaling
Performance optimization

Tutorial includes:

✔ Fine-tuning experiments
✔ Latency benchmarking

🧠 Vision Transformers — CNN Alternative

📄 Paper:
🔗 https://arxiv.org/pdf/2010.11929.pdf

Authors: Alexey Dosovitskiy et al.

What You Learn
Patch embeddings
Self-attention mechanism
Global context modelling

Tutorial includes:

✔ Transformer encoder implementation
✔ CNN vs ViT comparison
✔ Large dataset training strategy

🧪 Unified Training Pipeline
python train.py --model resnet50 --epochs 25 --batch_size 32

Includes:

augmentation
LR scheduler
mixed precision
early stopping
checkpointing
📊 Evaluation Metrics
Accuracy
Precision
Recall
F1 Score
Confusion Matrix
Class-wise analysis
📈 Visualization
Training curves
Prediction visualization
Grad-CAM heatmaps
Feature map inspection
🎥 Demo Inference
python predict.py --image sample.jpg --model efficientnet

Output:

Input image
Predicted class
Confidence score
Attention visualization
🧩 Future Roadmap

🚀 Swin Transformers
🚀 ConvNeXt
🚀 NAS architectures
🚀 AutoML tuning
🚀 Quantization
🚀 TensorRT deployment
