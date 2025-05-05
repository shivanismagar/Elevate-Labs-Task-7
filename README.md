# Elevate-Labs-Task-7
# 🧠 Support Vector Machines (SVM) - Breast Cancer Classification

## 🎯 Objective
Apply **Support Vector Machines** for binary classification using both **linear** and **RBF** kernels on the **Breast Cancer dataset**. Explore model tuning, cross-validation, and decision boundary visualization.

---

## 🧰 Tools & Libraries
- Python (scikit-learn, numpy, matplotlib, pandas)
- Breast Cancer Dataset from `sklearn.datasets`

---

## 🔬 Dataset Description
The dataset contains features computed from breast mass cell nuclei (e.g., radius, texture, perimeter) and a binary label indicating:
- **0** = Malignant
- **1** = Benign

---

## ✅ Tasks Covered
1. Load and explore dataset.
2. Normalize features using `StandardScaler`.
3. Train SVM classifier with:
   - Linear kernel
   - RBF kernel
4. Evaluate models using:
   - Accuracy
   - Confusion Matrix
   - Classification Report
5. Apply **cross-validation** to assess performance.
6. Use **GridSearchCV** to tune `C` and `gamma`.
7. Reduce dimensions using **PCA** for 2D visualization.
8. Plot **decision boundary** using PCA components.

---

## 📈 Results
- Best model achieved ~98% accuracy with RBF kernel after tuning.
- GridSearchCV revealed optimal parameters for `C` and `gamma`.
- Decision boundary plotted using PCA-reduced data.


