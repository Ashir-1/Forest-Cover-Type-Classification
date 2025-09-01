# 🌲 Forest Cover Type Classification

A machine learning project that predicts **forest cover types (7 classes)** from cartographic and environmental data.  
This project compares the performance of **Random Forest** and **XGBoost** classifiers on the **UCI Covertype Dataset**.

---

## 📊 Dataset
- **Source**: [UCI Covertype Dataset](https://archive.ics.uci.edu/ml/datasets/covertype)  
- **Samples**: 581,012  
- **Features**: 54 (both numerical and categorical)  
- **Target Variable**: Forest cover type (7 categories)

---

## ⚙️ Workflow
1. **Data Loading** – Load the UCI Covertype dataset  
2. **Preprocessing** – Standardize only the numerical features  
3. **Splitting** – Train-test split (80% training, 20% testing)  
4. **Model Training** – Random Forest & XGBoost for multi-class classification  
5. **Evaluation** – Metrics: Accuracy, Precision, Recall (using a 20% holdout test set)  
6. **Analysis** – Confusion matrices & feature importance visualization  

---

## 🏋️ Training Setup
- **Models**: Random Forest, XGBoost  
- **Objective**: Multi-class classification  
- **Validation**: 20% holdout test set  
- **Metrics**: Accuracy, Precision, Recall  

---

## 📈 Results
### 🔹 Random Forest
- Confusion Matrix: `RF_confusion_matrix.png`  
- Feature Importance: `RF_important_features.png`  

### 🔹 XGBoost
- Confusion Matrix: `XGB_confusion_matrix.png`  
- Feature Importance: `XGB_important_features.png`  

---

## 📦 Requirements
Make sure you have the following installed:

```bash
Python 3.12
pandas
scikit-learn
xgboost
matplotlib
seaborn
