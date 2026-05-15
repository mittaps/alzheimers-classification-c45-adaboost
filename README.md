# Alzheimer’s Disease Classification: C4.5 vs. Adaptive Boosting

## Project Overview
This repository contains a machine learning project focused on the classification of Alzheimer's Disease. It presents a comparative analysis between a traditional Decision Tree algorithm (C4.5) and an ensemble learning method (Adaptive Boosting / AdaBoost). The objective is to evaluate which algorithm provides higher accuracy, precision, and reliability when processing medical datasets.

## Dataset Information
* **Source:** https://www.kaggle.com/datasets/ninadaithal/imagesoasis
* **Data Preprocessing:** The preprocessing phase involved handling missing values, normalizing numerical features.

## Technology Stack
* **Programming Language:** Python
* **Data Manipulation:** Pandas, NumPy
* **Machine Learning:** Scikit-Learn
* **Data Visualization:** Matplotlib, Seaborn

## Methodology
1. **Exploratory Data Analysis (EDA):** Feature distributions and correlations were analyzed to identify significant predictors of the disease.
2. **C4.5 Decision Tree Model:** A baseline model was constructed using the C4.5 algorithm, utilizing entropy and information gain criteria for data splitting.
3. **Adaptive Boosting (AdaBoost) Model:** An ensemble classifier was trained to enhance predictive performance by iteratively addressing misclassified instances from the baseline model.
4. **Model Evaluation:** Both models were assessed using standard classification metrics: Accuracy, Precision, Recall, and F1-Score.

## Key Findings
* **C4.5 Performance:** Achieved an accuracy of 89.27%.
* **AdaBoost Performance:** Achieved an accuracy of 91.5%.
* **Conclusion:** The AdaBoost algorithm demonstrated superior performance compared to the C4.5 model, indicating its effectiveness in handling the non-linear complexities of this dataset.
