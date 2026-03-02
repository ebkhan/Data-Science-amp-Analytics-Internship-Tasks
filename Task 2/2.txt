Task 2: Credit Risk Prediction
Objective:
Predict whether a loan applicant is likely to default on a loan.

1)Importing libraries
2)Load data set of Loan from desktop
3)count the number of missing values in data se
4)Fill the missing values in data set
5)Visualize key features such as loan amount, education, and income for this i use
5.1)histogram to understand the distribution of numerical data like loanamount and applicantincome 
5.2)I have use countplot to visualize the frequency distribution of between Education vs loan variables.
5.3)I have use countplot to visualize the frequency distribution of between Education vs loan status.
6)Convert categorical to numerical such as loan status
7) Splitting data (80% Train, 20% Test) We do this to make sure your model isn't just memorizing the answers
8)I have choosen Logistic Regression model for model training because of its interpretability, stability, and regulatory acceptability, as it clearly explains how each feature affects the default probability 
9)confuse matrix to evaluate the performance of a classification model by comparing the predicted values with the actual values
10) classification report to measure the performance of a classification model beyond simple accuracy

Result:
1)Overall Accuracy (79%): At first glance, the model seems to be working well, as it gets 4 out of 5 applications correct.
2)When the model says "Approve," it is right 76% of the time. The other 24% are risky people it accidentally let through.
3)The model only caught 42% of the people who actually defaulted.
Insights
1)Income versus Loan Amount: The Debt-to-Income (DTI) ratio is just as important as your income. High earners who ask for too much money relative to their salary are seen as high risk.
2)Education Matters (a little): Graduates generally have higher incomes and slightly better approval rates, but it's less important than credit history.
