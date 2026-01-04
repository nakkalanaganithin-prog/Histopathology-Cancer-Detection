Project Overview
This project presents an histopathology cancer detection system designed to assist pathologists in identifying malignant tissue from microscopic biopsy images. The system leverages deep learning, meta-learning, and rule-based inference to improve diagnostic accuracy, consistency, and efficiency.
The approach focuses on patch-level analysis of high-resolution histopathology images, followed by tissue-level aggregation to produce a final diagnosis.
Methodology
The system follows a multi-stage pipeline:
Input Tissue Image
Patch Extraction from large biopsy images
Patch-level CNN Classification
Meta-classifier Aggregation of patch predictions
Rule-based Severity Engine
Final Tissue-level Diagnosis
This hybrid design combines the strengths of deep learning models and rule-based logic for robust cancer detection.
System Architecture
Patch-level CNN
Extracts features and classifies individual image patches
Meta-classifier
Aggregates multiple patch predictions into a tissue-level decision
Rule-based Engine
Handles patch inconsistencies and infers severity
Dataset
Source: Kaggle – Histopathologic Cancer Detection Dataset
Total Images: 220,000
Classes:
Cancer: 110,000 (50%)
Non-Cancer: 110,000 (50%)
The dataset is balanced, making it suitable for reliable supervised learning.
Results & Performance
Patch-level CNN Accuracy: ~99.98% (expected)
Meta-classifier Improvement:
Accuracy gain: 2% – 6%
Weighted F1-score improvement: up to 18%
Overall System Goal:
90% accuracy at tissue level with improved robustness
