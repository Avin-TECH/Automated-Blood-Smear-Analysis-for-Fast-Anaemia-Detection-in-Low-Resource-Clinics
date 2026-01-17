# Automated-Blood-Smear-Analysis-for-Fast-Anaemia-Detection-in-Low-Resource-Clinics
Architected and trained a convolutional neural network (CNN) based on VGG16 using transfer learning on the AneRBC dataset


Project Overview

Anemia is a widespread global health condition, particularly affecting low-resource regions where access to trained hematologists and laboratory infrastructure is limited. This project presents an automated deep learning–based system for fast and accurate anemia detection from microscopic blood smear images.

The system leverages transfer learning with a VGG16-based Convolutional Neural Network (CNN) to classify red blood cell (RBC) images as anemic or healthy, enabling decision support for clinical screening.

🎯 Objectives

Automate anemia detection using blood smear images

Reduce diagnostic time and dependency on manual microscopy

Build an end-to-end machine learning pipeline suitable for low-resource clinical settings

Achieve high accuracy while maintaining model robustness and interpretability

📊 Dataset

Dataset: AneRBC (Anemia Red Blood Cell Dataset)

Type: Microscopic blood smear images

Classes:

Anemic

Healthy

Note: The dataset is not included in this repository due to size and licensing restrictions.

📎 Dataset access details and expected directory structure are provided in data/README.md.

🧠 Methodology
Model Architecture

Base Model: VGG16

Strategy: Transfer Learning

Final layers fine-tuned for binary classification

Preprocessing & Augmentation

Image resizing and normalization

Data augmentation:

Rotation

Horizontal and vertical flipping

Zooming

Class balancing to handle data imbalance

Training

Optimizer: Adam

Loss Function: Binary Cross-Entropy

Evaluation Metrics:

Accuracy

Precision

Recall

Confusion Matrix

📈 Results

Final Accuracy: 94.85%

Strong recall for anemic class, critical for medical screening

Robust generalization on unseen test images

Key outputs:

Confusion Matrix

Training and validation curves

Sample prediction visualizations

All evaluation artifacts are available in the results/ directory.
