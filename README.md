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

---

## 💡 How to Run

1. **Clone the repository**  
   ```bash
   git clone https://github.com/YOUR_USERNAME/forest-cover-classifier.git
   cd forest-cover-classifier
