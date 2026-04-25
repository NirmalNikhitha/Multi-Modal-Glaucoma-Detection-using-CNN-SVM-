# Multi-Modal-Glaucoma-Detection-using-CNN-SVM-
Automated glaucoma detection system using CNN for feature extraction and SVM for classification on fundus image datasets (REFUGE, ORIGA).
📌 Overview

Glaucoma is a progressive eye disease that can lead to irreversible blindness if not detected early.
This project presents a hybrid CNN-SVM model to automatically detect and stage glaucoma using fundus images.

🎯 Objective
Detect glaucoma stages: Normal, Low, Medium, High
Improve accuracy using CNN (feature extraction) + SVM (classification)
Provide multi-language alerts (English, Tamil, Hindi, Malayalam)

🧪 Dataset
REFUGE Dataset
ORIGA Dataset
Split: 80% Training / 20% Testing

⚙️ Methodology
🔹 1. Preprocessing
RGB Conversion
Grayscale Conversion
Gaussian Filtering
🔹 2. Segmentation
Blood Vessel Extraction
Optic Disc Detection
K-Means Clustering
🔹 3. Feature Extraction (CNN)
Auto-correlation
Contrast
Entropy
Homogeneity
Statistical Features (Area, Perimeter, Aspect Ratio)
🔹 4. Classification (SVM)
Classifies into:
Normal
Low
Medium
High

🧠 Model Architecture
Fundus Image → Preprocessing → Segmentation → CNN → Feature Vector → SVM → Output
📊 Performance Metrics
Accuracy
Sensitivity
Specificity
Precision
Recall

🌍 Multi-Language Alert System
Provides:
Alert
Diagnosis
Remedy
Languages:
English
Tamil
Hindi
Malayalam

📈 Results
Improved accuracy using hybrid model
Reduced false positives
Better generalization on small datasets

📌 Conclusion
Automated glaucoma detection improves early diagnosis
Hybrid CNN-SVM enhances classification performance
Useful for remote healthcare applications
