## Credit Card Fraud Detection — Machine Learning Project

### Motivation
Fraud detection is a critical real-world challenge where the cost of missing fraudulent transactions is high and the data is heavily imbalanced.  
The goal of this project was to build an end-to-end pipeline capable of identifying fraud reliably while dealing with real-world constraints.

### Dataset
The project uses a large, realistic credit-card transactions dataset containing normal and fraudulent operations.  
Its strong class imbalance and rich behavioral attributes make it suitable for testing both feature engineering and model robustness.

Dataset source: https://www.kaggle.com/datasets/kartik2112/fraud-detection

### Work Overview
All development is contained in a single notebook: `fraud_detection_project.ipynb`, which includes:
- **Exploratory Data Analysis (EDA):** understanding distributions, patterns, and anomalies.
- **Unsupervised Learning:** clustering and dimensionality-reduction attempts to reveal hidden structure.
- **Feature Engineering:** temporal indicators (hour/weekend), distance features, previous-fraud ratios, and preprocessing steps.
- **Modeling:** Logistic Regression, Random Forest, XGBoost, TabNet, and a simple Neural Network.
- **Imbalanced Learning:** SMOTE and threshold adjustments.
- **Evaluation:** ROC-AUC, Precision, Recall, F1-score, and comparisons across all models.

### Result
The pipeline achieved strong ROC-AUC and competitive recall through a combination of engineered features, model tuning, and imbalanced-learning strategies.

**Collaborator**: [Omer Sade](https://github.com/omer-sade)
