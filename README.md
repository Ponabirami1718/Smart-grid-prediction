# Enhanced Smart Grid Stability Prediction Using Hybrid Machine Learning Techniques

This repository contains the source code, methodology, and results of our B.Tech project that focuses on improving the stability prediction of smart grids using hybrid ensemble machine learning models.

## 📘 Project Description

Smart grids face challenges with stability due to the integration of renewable energy sources and decentralized power generation. This project implements a hybrid ML-based approach to accurately predict grid stability using ensemble techniques like **Stacking Classifier** (XGBoost + LightGBM + CatBoost) combined with **SMOTE-Tomek** sampling and **Optuna** hyperparameter tuning.

Our model achieved **96.55% accuracy**, outperforming traditional models like Random Forest, SVM, and single XGBoost implementations.

## 📌 Objectives

- Predict grid stability using hybrid machine learning models.
- Handle class imbalance using SMOTE-Tomek.
- Enhance prediction accuracy via Optuna-based hyperparameter tuning.
- Compare performance across multiple ML algorithms.

## 🔍 Dataset

- **Source**: Karlsruhe Institute of Technology
- **Samples**: 10,000
- **Attributes**: 14 features including tau (reaction times), power, elasticity coefficients, and stability indicators.

## 🧠 Algorithms Used

- XGBoost (with and without tuning)
- LightGBM
- CatBoost
- AdaBoost with Random Forest base
- Stacking Classifier (XGBoost + LightGBM + CatBoost + Logistic Regression)
- SMOTE-Tomek for class balancing
- Polynomial Feature Engineering

## 🛠️ Tools and Libraries

- Python (Google Colab)
- Scikit-learn
- Pandas, NumPy
- Optuna (Hyperparameter tuning)
- Matplotlib, Seaborn (Visualization)
- XGBoost, LightGBM, CatBoost

## 📊 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- ROC-AUC
- Learning Curve
- Residual Analysis

## 🚀 Results

- Best accuracy of **96.55%** with the Stacking Classifier
- Improved stability prediction with hybrid model over single learners
- Balanced performance across stable and unstable classes
- Significant improvement in minority class prediction after using SMOTE-Tomek

## 📌 Future Scope

- Real-time deployment with streaming data
- Integration with IoT-based smart meters
- Use of deep learning and federated learning
- Feature selection via SHAP, PCA
- Reduced computation using model pruning and quantization

## 👥 Authors

- Bhagyashree.M – CB.EN.U4EEE23108
- Ponabirami.A – CB.EN.U4EEE23126
- Varshini.G.S – CB.EN.U4EEE23142
- Harshita.V.P – CB.EN.U4EEE23155

## 🏫 Institution

**Amrita School of Engineering, Coimbatore**  
Department of Electrical and Electronics Engineering  
Amrita Vishwa Vidyapeetham

## 📄 License

This project is for academic and educational use only.

---

