# Tyre Defect Detection System

## Overview

This project aims to automate tyre inspection using Deep Learning and Computer Vision techniques.

The system uses:

- MobileNetV2 for tyre/non-tyre classification
- YOLO for tyre defect detection and localization (under development)
- TensorFlow and Keras for model training and evaluation

## Features

- Tyre vs Non-Tyre Classification
- Deep Learning based Image Classification
- Transfer Learning using MobileNetV2
- Image Preprocessing and Augmentation
- Model Evaluation using Accuracy, Precision, Recall and Consusion Matrix
- Future YOLO-based Defect Localization

## Technologies Used

- Python
- TensorFlow
- Keras
- MobileNetV2
- YOLO
- NumPy
- Matplotlib
- Computer Vision
- Deep Learning

## Project Workflow

1. Collect and prepare tyre image dataset
2. Preprocess images
3. Train MobileNetV2 model
4. Evaluate model performance
5. Predict on unseen images
6. Detect defects using YOLO

### Evaluation Metrics

- Confusion Matrix
- Precision
- Recall
- F1-Score

## Folder Structure

```text
tyre-defect-detection/
│
├── notebook/
│   └── cnntyre_final.ipynb
│
├── models/
│   └── tyre_classifiercnn.keras
│
├── README.md
├── requirements.txt
└── .gitignore
```

## Future Improvements

- Real-time defect detection
- Web deployment using FastAPI
- Mobile application integration
- Improved defect localization using YOLO

## Author

Priyanshu Giri

B.Tech Computer Science & Engineering

International Institute of Information Technology, Bhubaneswar
