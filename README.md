# Walmart Online Transaction Prediction with Random Forest

## Description
This repository contains the analysis and code used to predict transactions made by Walmart customers based on online transaction data. We used a dataset that captures detailed information on user demographics, product categories, and purchase amounts.

### Dataset Description
The dataset provides relevant information such as:
- Unique user and product identifiers.
- Gender, age groups, masked occupation.
- City categories.
- Duration of stay in the current city.
- Marital status.
- Masked product categories.
- Transaction amounts.

This dataset is useful for studying purchase patterns, customer preferences, and other factors related to online transactions.

## Project Objective
The main goal was to build a **Random Forest** model to predict customer transactions based on the available data. We used supervised learning techniques to identify patterns that can predict future transactions.

## Methodology
1. **Data Loading and Preprocessing**:
   - The dataset was loaded from a CSV file.
   - Data cleaning: handling missing values, encoding categorical variables, and transforming relevant features.
   - **StandardScaler** was applied to normalize numerical features and improve model convergence.

2. **Random Forest Model**:
   - A Random Forest model was trained using the available features, such as product categories, demographic information, and purchase amounts.
   - Hyperparameters were tuned to enhance model performance.

3. **Model Evaluation**:
   - The model was evaluated using metrics such as accuracy, AUC (Area Under Curve), and cross-validation.
   - An analysis of model performance was carried out based on the available data.

4. **Results and Conclusion**:
   - Random Forest models were able to identify key patterns influencing transactions.
   - The analysis helps predict future transactions and provides valuable insights for decision-making in marketing and inventory management.

## Requirements
This project requires the following libraries:
- `pandas` for data manipulation.
- `scikit-learn` for model building.
- `matplotlib` and `seaborn` for data visualization.

Installation:
```bash
pip install pandas scikit-learn matplotlib seaborn
