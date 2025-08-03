# 💼 Arch Technology – Machine Learning Internship

Welcome to my project repository for the **Machine Learning Internship** at **Arch Technology**.  
This internship helped me gain hands-on experience in solving real-world ML problems using Python, scikit-learn, and essential data science tools.

---

## 📁 Tasks Overview

| Task | Title                    | Description                                               |
|------|--------------------------|-----------------------------------------------------------|
| **1** | Email Spam Classification | Build a binary classifier to detect whether a message is spam or ham. |
| **2** | MNIST Digit Recognition   | Build a multi-class digit classifier using the MNIST dataset.         |

---

## ✅ Task 1: Email Spam Classification

- **Objective**: Classify SMS messages as **spam** or **ham**.
- **Dataset**: `spam.csv` (labeled SMS text messages)
- **Key Techniques**:
  - Text preprocessing (lowercasing, punctuation removal, etc.)
  - TF-IDF Vectorization
  - Model training & evaluation

### 🔍 Models Compared:
- Logistic Regression
- Naive Bayes
- Support Vector Machine (SVM)
- Random Forest

### 📦 Outputs:
- Best model saved as `best_spam_model.pkl`
- Confusion matrix heatmap
- Accuracy and F1-Score comparison of all models

---

## ✅ Task 2: MNIST Digit Recognition

- **Objective**: Classify handwritten digits (0 to 9)
- **Dataset**: MNIST (70,000 grayscale 28x28 images)
- **Key Techniques**:
  - Image flattening & normalization
  - Pixel-based feature extraction
  - Model evaluation on multiclass classification

### 🔍 Models Used:
- K-Nearest Neighbors
- Logistic Regression
- Support Vector Machine (SVM)
- Random Forest

### 📦 Outputs:
- Confusion matrix for each model
- Accuracy score comparison
- Best model saved (optional): `best_mnist_model.pkl`

---

## 🧠 Skills Gained

- Text & image data preprocessing
- Supervised ML model building (binary & multiclass)
- Vectorization (TF-IDF, image flattening)
- Evaluation using confusion matrix, accuracy, F1-score
- Model pipelines & saving models using `joblib`

---

## 📂 Folder Structure

