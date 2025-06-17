# cnn-url-classifier

A deep learning-based classifier that detects and categorizes URLs as benign, defacement, malware, or phishing using a CNN model and engineered URL features.

## What This Project Does
- Uses a CNN built with PyTorch to classify URLs into four threat categories.
- Extracts 12 key features from URLs (e.g., length, subdomains, HTTPS usage).
- Applies normalization and one-hot encoding for training.
- Enhances detection using fuzzy matching via `rapidfuzz`.

## Results
- CNN Validation Accuracy: **81.91%**
- Baseline (Random Forest) Accuracy: **82.77%**
- Test Accuracy on unseen data: **30%**
- CNN shows strong in-distribution performance but limited generalization across sources.
