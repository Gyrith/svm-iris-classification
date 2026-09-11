# Iris Classification Project
Support Vector Machine (RBF kernel) classifier trained on the Iris dataset, with hyperparameter tuning via GridSearchCV and ROC/AUC evaluation.

## Contents
- `CG_C07_M06.ipynb` — full notebook: data loading & preprocessing, baseline SVM training, evaluation (confusion matrix, classification report), GridSearchCV tuning, and ROC curve/AUC analysis.

## Approach
1. Load and preprocess the Iris dataset (scaling, train/test split)
2. Train a baseline SVM with an RBF kernel
3. Evaluate with a confusion matrix and classification report
4. Tune hyperparameters (`C`, `gamma`) with GridSearchCV
5. Evaluate the optimized model with ROC curve and AUC

## Tech
Python, scikit-learn, pandas, matplotlib, seaborn