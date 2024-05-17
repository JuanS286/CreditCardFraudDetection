# Credit Card Fraud Detection

## Project Overview
This project aimed to develop machine learning models to predict whether a credit card transaction is fraudulent or legitimate. The objective was to enhance financial security, maintain consumer trust, reduce costs associated with fraud, and ensure regulatory compliance. The project utilized classification models, with XGBoost showing the highest performance.

## Objectives
1. Predict fraudulent transactions using machine learning.
2. Improve financial security and reduce fraud-related costs.
3. Maintain high consumer trust and regulatory compliance.

## Tools and Technologies
- **Machine Learning**: XGBoost, Random Forest
- **Data Handling**: `pandas`, `scikit-learn`, `imbalanced-learn` (SMOTE)
- **Evaluation Metrics**: Accuracy, Precision, Recall, F1-score

## Data Collection and Preprocessing
- **Dataset**: Sourced from credit card transaction records.
- **Preprocessing Steps**:
  - Feature engineering to convert and handle outliers and missing values.
  - Analysis of correlation between features.
  - Handling class imbalance by undersampling the majority class.

## Methodology
- **Modeling Process**:
  - Initial modeling with the unbalanced dataset resulted in poor performance.
  - Balanced the dataset using undersampling techniques, leading to improved results.
  - Applied both Random Forest and XGBoost models.

- **Evaluation**:
  - Used recall as the primary metric to measure how many fraudulent transactions were correctly identified.
  - Evaluated additional metrics such as accuracy, precision, and F1-score.

## Results and Comparison
- **XGBoost Performance**:
  - Achieved approximately 80% in all key metrics (accuracy, precision, recall, F1-score).
  - Addressed overfitting issues by fine-tuning the model, though with a slight trade-off in metric scores.

- **Random Forest Performance**:
  - Also performed well but was slightly less effective than XGBoost.

## Key Benefits
- **High Accuracy**: Reduced false positives and false negatives, ensuring smooth processing of legitimate transactions while flagging fraudulent ones.
- **Adaptive Learning**: Continuously learns from new transaction patterns.
- **Cost Efficiency**: Significantly lowers financial and operational costs associated with fraud.
- **Regulatory Compliance**: Helps financial institutions comply with fraud prevention regulations.


