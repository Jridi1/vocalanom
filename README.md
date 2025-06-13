# Gender Prediction by Voice using Machine Learning

This project focuses on predicting gender (male or female) based on human voice features using supervised machine learning techniques. It is inspired by the [Kaggle notebook by Farzona Eraj](https://www.kaggle.com/code/farzonaeraj/predict-gender-by-voice).

## 🧠 Overview

The goal is to train a classification model that can determine gender from voice characteristics such as frequency, jitter, shimmer, and harmonicity. The dataset contains pre-extracted acoustic features and the corresponding gender labels.

## 📁 Dataset

- **Source**: [Gender Recognition by Voice Dataset](https://www.kaggle.com/datasets/farzonaeraj/predict-gender-by-voice)
- **Features**: 
  - Acoustic properties like mean frequency, standard deviation, median, quartiles, skewness, kurtosis, jitter, shimmer, etc.
  - Target variable: `label` (male or female)

## ⚙️ Technologies & Tools

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-learn (SVM, Decision Tree, Random Forest, Logistic Regression)
- Jupyter Notebook

## 📊 Project Steps

1. **Data Exploration & Cleaning**  
   - Checked for missing values and outliers  
   - Visualized distributions of voice features by gender

2. **Feature Scaling**  
   - StandardScaler applied to normalize feature values

3. **Modeling**  
   - Trained several classifiers:
     - Support Vector Machine (SVM)
     - Decision Tree
     - Random Forest
     - Logistic Regression
   - Evaluated performance using accuracy, confusion matrix, and classification report

## 🔍 Key Insights

- Voice-based features are highly discriminative for gender classification
- Feature importance analysis shows frequency-related features are among the most influential
- SVM and Random Forest perform excellently without overfitting
## 📌 Credits

- Inspired by [Farzona Eraj's Kaggle notebook](https://www.kaggle.com/code/farzonaeraj/predict-gender-by-voice)
- Dataset by the same author, available on [Kaggle Datasets](https://www.kaggle.com/datasets/farzonaeraj/predict-gender-by-voice)

---
