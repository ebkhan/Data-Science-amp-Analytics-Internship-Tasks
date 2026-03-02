Objective:
Identify customers who are likely to leave the bank..
My Approach:
Objective:
Estimate the medical insurance claim amount based on personal data.
My Approach
1)Load dataset download from kaggle
2)Data cleaning(detect missing values)
3)Encode categorical features such as geography and gender into numerical because Machine learning models require numerical data.
4)Split the data into 80% training and 20% testing sets.
5)Model Selection:The Random Forest algorithm consistently outperforms simpler models like Logistic Regression in terms of accuracy, stability, and its capacity to handle complex banking data, making it a popular choice for predicting bank churn. 
6)Visualizing which features drive the model's decisions helps identify the biggest "red flags" for customer churn

Results
1)Success Rate: The model is about 86% accurate This means it correctly identifies most customers, but it is much better at spotting who will stay than who will leave.
2)88% predicted as stay actually stayed
3)only identifies 46% of actual churners, missing more than half (54%) of customers who are leaving

insights:
1)Older customers (ages 40–60) are much more likely to leave than younger ones
2)The customer churn percentage for customers in Germany is high (~32%) compared to those in France and Spain


