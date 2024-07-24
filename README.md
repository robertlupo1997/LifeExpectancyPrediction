Life Expectancy Prediction Project
Project Overview
This project aims to develop predictive models for life expectancy based on age and sex. Using life tables from the Human Mortality Database, we analyze and model the relationship between these factors to provide accurate life expectancy estimates.

Problem Statement
Develop models to predict life expectancy for males and females based on their age and sex.

Dataset
The dataset used in this project is derived from the Human Mortality Database. It includes the following columns:

Age
Sex (0 = male, 1 = female)
e(x)-Life Expectancy
Data Cleaning and Wrangling
The data was cleaned and wrangled to ensure its suitability for analysis:

Combined life tables of USA females and males.
Ensured no missing values were present.
Exploratory Data Analysis (EDA)
Key insights from EDA:

As age increases, life expectancy decreases.
On average, women live slightly longer than men.
Histograms and boxplots since 1933 display life expectancy frequencies and differences between genders.
Statistical Analysis
Hypothesis Testing
Performed a hypothesis test to check for a significant difference in mean life expectancy between males and females. The results indicate that:

Females have a higher mean life expectancy than males.
This difference is statistically significant.
Correlation Analysis
The correlation matrix suggests:

A strong negative linear relationship between age and life expectancy.
Gender as a binary variable has no meaningful correlation.
Regression Analysis
Approximately 94.59% of the variability in life expectancy is explained by age and gender.
For each year increase in age, life expectancy decreases by approximately 0.698 units, holding gender constant.
Females, on average, have a higher life expectancy than males by approximately 3.31 years, holding age constant.
Advanced Techniques
Ridge Regression
The model performs well with a low RMSE and high R-squared.
The selected lambda balances model complexity and goodness of fit.
Non-zero coefficients indicate important variables for prediction.
Support Vector Machine (SVM)
The model provides accurate predictions with a low RMSE and high R-squared.
Effective tool for predicting life expectancy based on given features.
Predictive Modeling
Hold-out Validation
80% of the dataset used for training.
20% of the dataset used for testing.
Model Evaluation
Linear Regression: Good predictive performance with moderate RMSE and high R-squared.
Support Vector Machine: Strong predictive performance with low RMSE and high R-squared.
Decision Tree: Good predictive performance with moderate RMSE and high R-squared.
Random Forest: Good performance but with relatively higher RMSE.
Gradient Boosting: Excellent predictive performance with low RMSE and high R-squared.
Conclusion
Limitations
Analysis based on a specific set of features (age and gender) may not consider other influencing factors.
Models assume a linear relationship between features and life expectancy, which may not capture complex non-linear patterns.
Improvements and Future Research
Feature Expansion: Explore additional features like socioeconomic factors, healthcare access, and lifestyle variables.
Model Complexity: Experiment with more complex models or ensemble methods.
Data Quality: Address any missing values, outliers, or inconsistencies.
Ethical Considerations: Ensure fairness and avoid biases in predictive models.
External Validation: Validate models on external datasets to assess generalizability and robustness.
Most models performed well, with Random Forests performing slightly worse than the others.

Acknowledgements
Thank you for reviewing this project! For more details and the dataset, visit the Human Mortality Database at mortality.org.
