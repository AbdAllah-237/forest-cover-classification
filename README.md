# 🌲 Forest Cover Type Classifier

A fast and efficient machine learning project that predicts the type of forest cover based on geographic and environmental features using the **Random Forest** algorithm.  
This is part of my Elevvo Machine Learning Internship Projects 🎯

---

## 🔍 Problem Statement

The dataset contains over 580,000 observations of forested areas with 54 features (elevation, soil type, distance to hydrology, hillshade, etc.) and a target label `Cover_Type` (1–7), indicating forest cover classes such as Spruce/Fir, Lodgepole Pine, etc.

---

## 🧠 Model Overview

- ✅ **Model Used**: Random Forest Classifier  
- ⚙️ **Preprocessing**:
  - Feature sampling (30,000 samples for speed)
  - SMOTE (to balance class distribution)
- 📈 **Performance**:
  - Accuracy: **~83%**
  - Fast training time (optimized for GitHub/Colab runtime)

---

## 🔧 Tech Stack

- Python (Pandas, NumPy)
- Scikit-learn (RandomForestClassifier, train_test_split, accuracy_score)
- imbalanced-learn (SMOTE)
- Seaborn + Matplotlib (for visualizations)

---

## 📊 Visualizations

- Class distribution
- Confusion matrix
- Feature importance (Top 20)
- Accuracy bar plot

All are auto-generated with clean plots and saved under `assets/plots/` (optional step).
## 🔗 Run on Google Colab

Click below to view and run the full project with interactive output:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1G8gEftFmdz-idCSSbOD98Y8WFea3uh4O?usp=sharing)

---
