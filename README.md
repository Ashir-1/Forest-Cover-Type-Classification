#🌲 Forest Cover Type Classification

A machine learning project for predicting forest cover types (7 classes) using cartographic and environmental data.
The system compares the performance of Random Forest and XGBoost classifiers on the UCI Covertype Dataset.

#📊 Dataset

Source: UCI Covertype

Size: 581,012 samples

Features: 54 (mixed numerical & categorical)

Target: Forest cover type (7 classes)

#⚙️ Workflow

Data Loading – Import the UCI Covertype dataset

Preprocessing – Standardize numerical features

Splitting – 80% training, 20% testing

Model Training – Random Forest & XGBoost (multi-class classification)

Evaluation – Accuracy, Precision, Recall on holdout set

Analysis – Feature importance & confusion matrices

#🏋️ Training Setup

Models: Random Forest, XGBoost

Task: Multi-class classification

Validation: 20% holdout test set

Metrics: Accuracy, Precision, Recall

📈 Results
Random Forest

Confusion Matrix: RF_confusion_matrix

Top Features: RF_important_features

XGBoost

Confusion Matrix: XGB_confusion_matrix

Top Features: XGB_important_features

🔧 Requirements

Python 3.12

pandas

scikit-learn

xgboost

matplotlib

seaborn
