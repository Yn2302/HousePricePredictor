## Overview
This project aims to predict house prices based on a dataset obtained from Kaggle. The data is imported as an Excel file and undergoes a thorough data cleaning and analysis process. Two regression models, k-Nearest Neighbors (KNN) and Random Forest, are employed to predict house prices. The analysis includes data imputation, outlier removal, visualization of correlations, and model comparison.

## Dataset
The dataset used in this project is sourced from Kaggle and is provided in Excel format. The data contains information on various factors that may influence house prices.

## Data Cleaning
The data cleaning process involves several steps:
- Imputation: Missing values in columns with at least 50% values are imputed.
- Removal: Columns with 100% missing values are removed.
- Outlier Handling: Outliers are identified and removed from the dataset.
- Categorization: Different types of housing/buildings are separated into their own categories for more granular analysis.

## Exploratory Data Analysis (EDA)
EDA is performed to understand the relationships between different factors and house prices. Correlation matrices and visualizations are used to identify patterns and insights.

## Data Splitting
To evaluate model performance, the dataset is split into an 80/20 ratio for training and testing. This ensures that the models are tested on unseen data to assess their generalization capabilities.

## Models Used
Two regression models are implemented:
1. **k-Nearest Neighbors (KNN) Regression**
2. **Random Forest Regression**

After coding and evaluating both models, it was observed that Random Forest Regression outperformed KNN Regression. The decision was based on comparing testing and training data, considering the benefits of Random Forest's use of bootstrapping and boosting compared to the similarity-based learning approach of KNN.

## Conclusion
In conclusion, the Random Forest Regression model is chosen as the better fit for predicting house prices in this specific context. The analysis and code for this project are available in the repository.
