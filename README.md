# Emotion Recognition System

🚀 Overview

This project aims to classify emotions from speech using deep learning techniques. The model uses audio features such as Mel-frequency cepstral coefficients (MFCCs) and spectrograms to predict emotions like happiness, sadness, anger, fear, and others.

The model is built using deep learning techniques that process audio files to extract relevant features and train a classifier. 

The key components of the project include:

MFCCs (Mel-frequency cepstral coefficients): A representation of the short-term power spectrum of sound.
Spectrograms: Visual representations of the spectrum of frequencies in a sound signal.

Key Features:
Speech-based Emotion Classification: Predicts emotions based on speech data.
Data Augmentation: Uses various techniques to enhance the dataset and improve model performance.
Training: Implements training scripts to develop a robust emotion recognition model.
Evaluation: Includes scripts to assess the model’s performance on unseen data.

## Project Directory Structure

```plaintext
Emotion-Recognition-System/
├── data/                     # Folder for dataset
├── models/                   # Folder for saving trained models
├── notebooks/                # Jupyter Notebooks for analysis
├── src/                      # Source code for preprocessing, training, evaluation
│   ├── preprocessing.py      # Data preprocessing script
│   ├── model.py              # Model definition script
│   ├── train.py              # Training script
│   └── evaluate.py           # Evaluation script
├── README.md                 # Project description and setup instructions
└── requirements.txt          # Dependencies list
```
