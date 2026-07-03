# Multi-Modal Glaucoma Detection using CNN-SVM Hybrid Model

## Overview

This repository presents a hybrid deep learning and machine learning approach for automated glaucoma detection and staging using retinal fundus images. The proposed framework combines **Convolutional Neural Networks (CNN)** for feature extraction with **Support Vector Machine (SVM)** for classification, enabling accurate identification of glaucoma stages from retinal images. The system is evaluated using publicly available fundus image datasets and analyzed through multiple performance metrics.

---

## Features

- Automated glaucoma detection from fundus images
- Image preprocessing and segmentation
- CNN-based deep feature extraction
- SVM-based glaucoma classification
- Multi-stage glaucoma detection
- Performance evaluation using standard metrics
- CNN training and validation analysis

---

## Dataset

- REFUGE Dataset
- ORIGA Dataset

**Dataset Split**

- Training: 80%
- Testing: 20%

---

## Tools & Technologies

- Python
- TensorFlow / Keras
- OpenCV
- Scikit-learn
- NumPy
- Matplotlib

---

## Repository Contents

```
├── Dataset/
│   └── Fundus Images
├── Image_Preprocessing/
├── Segmentation/
├── Feature_Extraction/
├── CNN_Training/
├── Classification/
├── Performance_Metrics/
├── Results/
├── Main_Program.pdf
└── README.md
```

---

## Methodology

### Image Preprocessing

- RGB to Grayscale Conversion
- Image Enhancement
- Noise Reduction using Gaussian Filtering

### Segmentation

- Blood Vessel Extraction
- Optic Disc Detection
- K-Means Clustering

### Feature Extraction

Deep features are extracted using a Convolutional Neural Network (CNN), along with statistical image features for improved representation.

### Classification

The extracted feature vectors are classified using a Support Vector Machine (SVM) into the following categories:

- Normal
- Low Glaucoma
- Medium Glaucoma
- High Glaucoma

---

## Simulation Results

### Image Preprocessing

Enhances retinal images by reducing noise and improving image quality.

### Segmentation Module

Identifies important retinal structures such as blood vessels and optic disc.

### Feature Extraction

CNN extracts discriminative features required for glaucoma classification.

### CNN Training Graph

Shows the convergence of training and validation accuracy during model training.

### Performance Metrics

The model is evaluated using:

- Accuracy
- Precision
- Recall
- Sensitivity
- Specificity
- F1-Score

### Result

The hybrid CNN-SVM model successfully classifies retinal fundus images into different glaucoma stages with improved classification performance.

---

## Applications

- Computer-Aided Glaucoma Diagnosis
- Ophthalmology Screening Systems
- Clinical Decision Support
- Medical Image Analysis
- AI-Based Healthcare
- Eye Disease Detection
- Early Vision Loss Prevention
- Intelligent Diagnostic Systems

---

## Learning Outcomes

- Medical image preprocessing
- Image segmentation techniques
- CNN-based feature extraction
- SVM classification
- Performance metric evaluation
- Deep learning for medical imaging
- Hybrid AI model development


## License

This project is shared for educational and research purposes.
