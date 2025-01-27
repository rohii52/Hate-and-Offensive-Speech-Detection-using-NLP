# Hate and Offensive Speech Detection using NLP

This repository contains the code, datasets, and supplementary resources for detecting hate speech and offensive language in multiple languages using Natural Language Processing (NLP). The work leverages both traditional Machine Learning (ML) models and advanced Deep Learning (DL) and Transfer Learning (TL) techniques to identify hate speech across Tamil, English, German, and Arabic datasets.

---

## Overview

Hate speech and offensive language are significant concerns on online platforms, posing threats to societal harmony and individual well-being. This project aims to develop efficient, multilingual hate speech detection models to address these challenges, using cutting-edge NLP techniques. The models are evaluated for their performance, particularly in low-resource settings, and compared against data augmentation strategies to enhance effectiveness.

---

## Repository Structure

- **Datasets**: Multilingual datasets (Tamil, Arabic, English, German) used for training and testing.
- **Exploratory Data Analysis**: Scripts and notebooks for analyzing dataset distributions, text length, and token frequency.
- **Hate Speech Detection Code Files**: Code for preprocessing, model training, and evaluation.
- **Paperwork**: Documentation related to project management.
- **Reference Papers**: Collection of academic references.

---

## Methodology

### Preprocessing
1. Text Cleaning
2. Tokenization
3. Stopword Removal
4. Stemming and Lemmatization
5. TF-IDF Vectorization

### Models
- **Machine Learning Models**: SVM, Logistic Regression, Random Forest, K-Nearest Neighbors.
- **Deep Learning Models**: RNN, LSTM, Bi-LSTM.
- **Transfer Learning**: BERT.

### Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1 Score

---

## Results and Key Findings

1. Traditional ML models outperformed DL and TL models for smaller datasets (Tamil, Arabic).
2. BERT excelled in high-resource settings.
3. Data augmentation improved performance for low-resource datasets.

---

## Future Work

- Explore multimodal hate speech detection combining text and images.
- Implement cross-platform and cross-lingual detection systems.
- Investigate real-time hate speech intervention techniques.

---

## Acknowledgements

This project was conducted as part of an MSc Data Science dissertation at the University of Nottingham. Supervised by Dr. Milena Radenkovic, the research benefitted from valuable feedback and support.

---

## Citation

If you use any part of this repository, please cite:

**Rohith Ganesan**  
*Multilingual Hate Speech and Offensive Language Detection Using NLP*  
University of Nottingham, 2024
