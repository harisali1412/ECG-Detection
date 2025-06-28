# ECG-Detection

Overview
This project presents a comprehensive workflow for analyzing and classifying ECG images, enabling the early detection of cardiac abnormalities. Using a dataset of 99,199 ECG images across six heartbeat categories, the pipeline leverages advanced preprocessing, synthetic data generation, and machine learning models for robust classification.

Key Features
Dataset: Large-scale ECG dataset with six heartbeat categories (F, M, N, Q, S, V).
Preprocessing: Includes resizing, grayscale conversion, normalization, and noise removal.
Class Imbalance Handling: Utilizes SMOTE and GAN-enhanced SMOTE for synthetic sample generation.

Models:
SimCLR for unsupervised feature learning.
Random Forest for supervised classification.
Evaluation: 10-fold cross-validation with metrics like precision, recall, and F1-score.

Future Enhancements
Fine-tuning SimCLR with domain-specific augmentations.
Exploring hybrid models (e.g., CNNs + LSTMs).
Real-time ECG signal integration for clinical applications.

Impact
This project demonstrates the potential of self-supervised learning and ensemble techniques in advancing ECG-based diagnostics, contributing to improved cardiac healthcare solutions.
