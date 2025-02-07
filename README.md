# NFL_Play_Type_Prediction_Using_Machine_Learning

#### Project Title: NFL Play Type Prediction Using Machine Learning

#### Description:
This project focuses on predicting NFL play types (pass or run) using machine learning models. The goal is to analyze various game features and their influence on play-calling decisions. The project involves data cleaning, exploratory data analysis (EDA), feature engineering, model development, and evaluation. Two models, Random Forest and Gradient Boosting, were developed and compared, with Gradient Boosting selected as the final model due to its slightly superior performance.

#### Key Features:
- **Data Cleaning:** Handled missing values, removed irrelevant columns, addressed outliers, and standardized numerical features.
- **Feature Engineering:** Created new features such as 'Momentum,' 'Time Pressure,' and 'Team Mismatch' to capture game dynamics.
- **Exploratory Data Analysis (EDA):** Analyzed the distribution of play types and investigated the relationship between game features and play-calling decisions.
- **Model Development:** Developed and evaluated Random Forest and Gradient Boosting models.
- **Model Evaluation:** Compared model performance using precision, recall, F1-score, and accuracy metrics.
- **Results:** Applied the final model to a test dataset and analyzed its performance.

#### Files:
- **NFL_Play_Type_Prediction.ipynb:** Jupyter notebook containing the complete analysis, including data cleaning, EDA, model development, and evaluation.
- **Training_Data-1.xlsx:** Training dataset used for model development.
- **Testing_Data-1.xlsx:** Testing dataset used for model evaluation.
- **NFL_Play_Type_Prediction.dox**  Detailed report with analysis

#### Requirements:
- Python 3.x
- Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn, xgboost

#### Results:
- **Model Performance:** The Gradient Boosting model achieved an accuracy of approximately 66.48% on the test dataset.
- **Key Features:** The most significant features influencing play type predictions were 'TO GO,' 'DOWN,' and 'YARD LINE 0-100.'
- **Strategic Insights:** The analysis provides valuable insights for football coaches to optimize play-calling strategies based on game dynamics.

#### Conclusion:
The project successfully developed a machine learning model to predict NFL play types, offering valuable insights for game strategy and decision-making. The model's performance can be further improved by refining its sensitivity to pass plays and reducing false positives for runs. These insights can be leveraged to enhance real-time decision-making tools, providing a competitive edge in football strategy.

#### Contributors:
**Akhila Singaraju**
