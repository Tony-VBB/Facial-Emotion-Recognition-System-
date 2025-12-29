# Facial Emotion Recognition System

## Overview
This project implements a Facial Emotion Recognition system using Deep Learning to classify human emotions from facial images. The model is trained and evaluated on the FER-2013 dataset and supports real-time emotion detection from images or webcam input.

## Problem Statement
Understanding human emotions from facial expressions is crucial for applications in human-computer interaction, healthcare, education, and intelligent automation systems.

## Dataset
- **FER-2013**
- ~35,000 grayscale facial images
- 7 emotion classes: Angry, Disgust, Fear, Happy, Sad, Surprise, Neutral

## Approach
- Data preprocessing: normalization, resizing, augmentation, class balancing
- Model architecture: CNN / Transfer Learning (DenseNet / custom CNN)
- Training optimizations: weighted loss, learning rate scheduling, early stopping
- Evaluation using accuracy, loss curves, and confusion matrix

## Results
- Achieved stable training with strong generalization
- Improved performance using augmentation and balanced sampling
- Model evaluated using confusion matrix and class-wise accuracy

## Tech Stack
- Python
- PyTorch / TensorFlow
- OpenCV
- NumPy, Matplotlib, Seaborn
- Streamlit (for deployment)

## How to Run
```bash
pip install -r requirements.txt
python app.py
