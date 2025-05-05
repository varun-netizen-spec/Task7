# 🧠 Breast Cancer Detection using Support Vector Machines (SVM)

This project applies **Support Vector Machines (SVM)** to the **Breast Cancer Wisconsin Dataset** from Kaggle for binary classification. It features both **Linear** and **RBF kernels**, beautiful **PCA-based decision boundary visualizations**, and **hyperparameter tuning**.

---

## 📌 Project Objectives

- Perform binary classification to detect **malignant** and **benign** tumors.
- Use **SVM with Linear and RBF kernels**.
- Visualize decision boundaries using **PCA for 2D projection**.
- Evaluate performance using **confusion matrix and classification report**.
- Perform **hyperparameter tuning** with GridSearchCV.
- Provide interview-level understanding of SVM concepts.

---

## 🛠️ Tech Stack

- Python 🐍
- Scikit-learn
- Matplotlib / Seaborn
- NumPy / Pandas

---

## 📁 Dataset

- Source: Kaggle’s Breast Cancer Wisconsin (Diagnostic) Dataset  
- Link: [Download from Kaggle](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)

---

## 📊 Visualizations

- **PCA projection** of high-dimensional data to 2D
- **Decision boundary plots** for both linear and non-linear SVM
- **Heatmap of confusion matrix**

---

## 🧪 How to Run

1. Clone this repository or download the `.ipynb` notebook.
2. Install required packages:
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn
3.Run the Jupyter notebook to:

Load and preprocess data

Train SVM models

Visualize decision boundaries

Evaluate models

Tune hyperparameters

🎯 Results
Linear SVM is effective but limited for non-linear patterns.

RBF Kernel SVM performs significantly better with better boundary separation.

Hyperparameter tuning with GridSearchCV improved model accuracy.
