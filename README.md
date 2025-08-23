MultiScale_OCAD: Is An advanced anomaly detection model combining multi-scale feature extraction with One-Class SVM for industrial defect detection. 
Uses a Wide ResNet-50-2 backbone to extract hierarchical features from multiple network layers, enhanced with comprehensive data 
augmentation and automated hyperparameter optimization.

Key Features: Multi-layer feature extraction from pretrained CNN, Automated OCSVM parameter tuning with GridSearch, Advanced data augmentation pipeline, Precision-Recall and score distribution visualization, GPU-accelerated processing

Usage: Designed for Google Colab environment. Prepare your data in /anomaly_data/ with good/ and bad/ subdirectories, then run the full pipeline from feature extraction to model evaluation.
