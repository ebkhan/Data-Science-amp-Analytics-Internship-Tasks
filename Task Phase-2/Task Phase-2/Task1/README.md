Task objective:
Predict whether a bank customer will subscribe to a term deposit as a result of a marketing campaign.

My Approach:
1)Load dataset into jupyter download from Bank Marketing Dataset (UCI Machine Learning Repository)
2)Separating data values
3)Data cleaning such capitalize the first letter of strings and renaming columns  
  checking duplicate values and Null values
4)Exploratory Data Analysis (EDA):
The dataset was divided into training and testing sets to train the models and evaluate their performance on unseen data.
Visualizing of Age of Subscriber using histograms and Term Deposit Subscription Distribution using count polt.
5)preprocessing:
Encode Categorical Features
Split Features and Target:The dataset was divided into training and testing sets to train the models and evaluate their performance on unseen data.
6)Model use for Training:Logistic Regression
7)The models were evaluated using metrics such as the Confusion Matrix, F1-score, and the ROC Curve to assess how well the models predicted customer subscription behavior.
8)Model Interpretation:
SHAP was used to explain at least five individual predictions and identify the features that most influenced the model’s decisions.


Results and findings:
1)The ROC curve showed that the models were able to distinguish between customers who subscribe and those who do not. A higher AUC (Area Under the Curve) value indicated better model performance.
2)Important factors influencing customer subscription included call duration, previous campaign outcome, account balance, and contact month.
3)The analysis showed that customers with longer call durations and positive outcomes in previous campaigns were more likely to subscribe to a term deposit.


