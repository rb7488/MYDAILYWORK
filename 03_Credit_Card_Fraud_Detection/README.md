# Credit Card Fraud Detection 🛡️

## Overview
This project focuses on detecting fraudulent credit card transactions using machine learning. Due to extreme class imbalance, traditional accuracy-based evaluation is avoided.

## Dataset
- Source: Kaggle (Credit Card Fraud Detection)
- Fraud transactions: ~0.17%
- Target: Class (0 = Genuine, 1 = Fraud)

## Approach
- Data preprocessing and scaling
- Logistic Regression (baseline + tuned)
- Random Forest (baseline + tuned)
- Threshold tuning to balance precision and recall

## Evaluation Metrics
- Precision
- Recall
- F1-score
- Confusion Matrix

## Conclusion
Threshold-tuned Random Forest achieved the best balance between fraud detection and false positives, making it suitable for real-world deployment.

---
**Internship Task – Data Science**
