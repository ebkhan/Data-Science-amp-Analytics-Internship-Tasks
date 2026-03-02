Objective:
Estimate the medical insurance claim amount based on personal data.
My Approach
1)Load dataset download from kaggle
2)Data cleaning(detect missing values)
3)Data Preprocessing (Handled categorical variables (sex,smoker,region) using One-Hot Encoding).
4)Split the data into 80% training and 20% testing sets.
5)Model Selection:Implemented a Linear Regression model as the baseline for predicting continuous numerical values 
6)Evaluation: Measured the variance explained by the model using the R2 Score and the MAE and RMSE to quantify prediction errors.
7)Visualize how BMI, age, and smoking status impact insurance charges.

Result:
R²Score: (~0.78):The model explains 78% of the data variance.
MAE:The average prediction error (MAE) is $4,18
RMSE: $5,796 (a higher value indicates sensitivity to outliers with high costs).

insights:
1)The most significant contributor to high insurance costs is smoking.
2)BMI has a significant impact on fees, primarily for people who smoke
3)Medical costs increase linearly and consistently with age.