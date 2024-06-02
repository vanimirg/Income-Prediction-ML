# Adult Census Income Prediction using Machine Learning

## Project Overview

This project aims to predict whether an individual's income exceeds $50,000 per year based on various demographic and professional attributes. The dataset includes information such as age, workclass, education, occupation, and more. The objective is to build a predictive model that can help identify key factors influencing income levels and accurately classify individuals' income categories.

## Data Source
https://www.kaggle.com/datasets/uciml/adult-census-income

## Methodology

### Data Collection

The dataset used in this project is sourced from the UCI Machine Learning Repository and contains various demographic and professional attributes of individuals.

### Data Preprocessing

Data preprocessing steps included handling missing values, encoding categorical variables, and scaling numerical features. Specific steps involved:
- Encoding categorical features using one-hot encoding.
- Handling missing values using appropriate imputation techniques.
- Normalizing numerical features for better model performance.

### Exploratory Data Analysis (EDA)

EDA was conducted to understand the distribution of features and their relationships with the target variable (income). Visualizations such as histograms, bar plots, and box plots were created to illustrate key patterns and insights.

### Model Building

Several machine learning models were built and evaluated to predict income categories. Models used include:
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Gradient Boosting Classifier

### Model Evaluation

Models were evaluated using metrics such as accuracy, precision, recall, F1-score, and ROC-AUC. Cross-validation techniques were used to ensure robust model performance.

## Results

Key findings from the analysis include:
- Education level and occupation are significant factors influencing income levels.
- Marital status and age also play important roles in determining income categories.
- The Gradient Boosting Classifier showed the best performance with high accuracy and ROC-AUC.

## Conclusion and Future Work

The analysis provides valuable insights into factors affecting income levels. Future work could focus on deploying the model to assist in real-time decision-making and further refining the model with additional data. Moreover, feature engineering and hyperparameter tuning could be explored to enhance model performance.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
