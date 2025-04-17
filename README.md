# 👶 Infant Cry Analysis using Machine Learning

An AI-powered system that classifies infant cries into distinct categories like **Hungry**, **Tired**, **Discomfort**, **Burping**, and **Belly Pain** using audio signal processing and machine learning techniques.

---

## 📌 Objective

The goal of this project is to design an intelligent system capable of understanding an infant’s needs by analyzing their cry patterns using audio classification techniques. This can assist parents and caregivers in identifying the possible reasons behind a baby’s cry in real-time.

---

## 🧠 Techniques Used

- **Audio Preprocessing**: Silence trimming, duration standardization (3 seconds), padding
- **Feature Extraction**:  
  - MFCC (Mel-Frequency Cepstral Coefficients)  
  - Chroma Features  
  - Spectral Contrast  
- **Machine Learning Models**:  
  - Random Forest  
  - Support Vector Machine (SVM)  
  - Decision Tree
- **Deep Learning Models**:
  - CNN - LSTM Model
- **Ensemble Learning**:  
  - Stacking Classifier combining all three models for improved accuracy
- **Data Augmentation**:  
  - Time Stretching  
  - Pitch Shifting  
  - Adding Background Noise
- **Visualization**:  
  - Waveforms  
  - Spectrograms  
  - Confusion Matrix  
  - Accuracy/Loss Plots

---

## 📊 Dataset Overview

- **Total Samples**: ~880 audio clips after augmentation
- **Classes**:  
  - Tired: 176  
  - Hungry: 176  
  - Discomfort: 176  
  - Burping: 176  
  - Belly Pain: 176  
- **Format**: `.wav` files (3 seconds each, 22050Hz)

---

## 📁 Project Structure
  - AudioAugment1.ipynb
      - Contains code to Augment the Audio Files
  - AudioFeatureExtraction.ipynb
      - Code for Feature Extraction Using MFCC, Chroma Features, Mel Spectrogram
  - AudioFeaturePreprocess.ipynb
      - Code for Model Training and Evaluation with the required Visuals.

---

## ✅ Model Performance

- **Random Forest**: 72% accuracy  
- **Support Vector Machine (SVM)**: 56% accuracy  
- **Decision Tree**: 50% accuracy  
- **Ensemble Model (Voting Classifier)**: *Under Development*

> Evaluation metrics include confusion matrices and classification reports.

---

## 🛠 Tools & Libraries Used

- Python  
- Google Colab  
- Librosa  
- NumPy & Pandas  
- Matplotlib & Seaborn  
- Scikit-learn  
- Joblib  
- Google Drive API (for data/model storage)

---

## 📌 Current Focus

- Learning advanced Deep Learning Architectures (CNNs, LSTMs, etc.)  
- Exploring NLP-based approaches (Transformers, Text Classification)  
- Implementing Ensemble Learning Techniques  
- Deploying and optimizing AI models

---

## 👤 About Me

I’m a passionate tech enthusiast with deep interest in:

- 🤖 Machine Learning & Artificial Intelligence  
- 💬 Natural Language Processing   
- 🌐 Web Development  
- 📊 Data Analytics & Visualization

---
## 🚀 How to Run the Project

> This project was developed and tested using [Google Colab](https://colab.research.google.com/).

1. **Clone the Repository**  
```bash
git clone https://github.com/Lokeshwari0506/infant-cry-analysis.git
cd infant-cry-analysis



