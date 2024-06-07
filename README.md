# Employee-Salary-Prediction

This repository contains a project aimed at predicting the salary of employees based on various features such as job type, degree, major, industry, years of experience, and distance from the metropolis. The dataset used for this project includes 1,000,000 samples, although the current model training uses only 50,000 samples for faster computation.

## Table of Contents

- [Problem Statement](#problem-statement)
- [Solution Approach](#solution-approach)
- [Model Performance](#model-performance)
- [Instructions](#instructions)
- [Results and Conclusion](#results-and-conclusion)
- [Future Work](#future-work)
- [License](#license)

## Problem Statement

To predict the salary of an employee based on the information provided in the dataset. The features include:

- Job Type
- Degree
- Major
- Industry
- Years of Experience
- Distance from Metropolis

## Solution Approach

1. **Exploratory Data Analysis (EDA)**: Understand the dataset, visualize distributions, and identify correlations.
2. **Data Preprocessing**: Handle missing values, encode categorical features, and scale numerical features.
3. **Model Building**: Train multiple regression models including Linear Regression, Decision Tree, Random Forest, and Gradient Boosting.
4. **Model Evaluation**: Evaluate models using metrics like RMSE, MAE, and R^2 score.
5. **Hyperparameter Tuning**: Optimize model performance using Grid Search and Cross-Validation.
6. **Feature Importance**: Analyze and visualize the importance of different features in predicting the salary.

## Model Performance

The models were trained on 50,000 samples from the dataset. The performance metrics on both training and testing sets are as follows:

- **Root Mean Squared Error (RMSE)**
- **Mean Absolute Error (MAE)**
- **R^2 Score**

**Note**: Using the complete dataset of 1,000,000 samples will likely improve the model performance, albeit with increased computation time.

## Results and Conclusion

The model provides a salary prediction range for new employees based on their job details. For instance, given the following employee details:
- **Job Type**: CTO
- **Degree**: Masters
- **Major**: Biology
- **Industry**: Health
- **Experience**: 17 years
- **Miles from Metropolis**: 9

The model predicts a salary range of \$175,000 - \$190,000.

### Insights:
- Major dissatisfaction among employees regarding salaries despite having the required skills.
- Employees living in metro cities are generally satisfied with their salaries, whereas those living farther are not.

### Recommendations:
1. Increase salaries for qualified employees.
2. Provide accommodation for employees living far from the city.
3. Offer appraisals or tokens of appreciation to improve employee loyalty.

## Future Work

1. Train the model on the complete dataset for better performance.
2. Explore other advanced regression techniques.
3. Implement model deployment for real-time salary predictions.

