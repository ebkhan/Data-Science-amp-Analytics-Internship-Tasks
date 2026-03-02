Objective:
Predict which customers are likely to accept a personal loan offer.
Approach:
1) I fetched the dataset using the ucimlrepo library from uci machine learning repository bank marketing using id.
2)I made sure that all features, such as age, job, and marital status, were correctly mapped.
3)I checked for missing values and found that the data was clean, with no "unknown" strings or NaNs. This allowed me to proceed without dropping any rows. 
4)Visualization of Age Distribution,Job Type and Marital Status
5)I converted categorical variables, like job and education, into numerical format using One-Hot Encoding
6)This made it possible for the mathematical models to process them. 
7)Modeling: I trained a Decision Tree Classifier. I chose this model because it is easy to understand, allowing the bank to see the exact rules used for predictions, such as "If Age > 60 and Balance > 500, then high probability."
8)Business insight extraction from data

insights:
1)High earners who use their cards frequently are seen as top-tier customers. If you have a high income and high monthly spending, banks view you as someone who can generate profit for them while clearly having the means to pay it back
2) Applicants with a clean credit history (no previous defaults) have a much higher chance of approval.
3)Customers with advanced degrees (Graduate or Professional) show a higher propensity for loan acceptance compared to those with only undergraduate education.
Result:
1)Looking at the bank data shows something clear - past money behavior matters more than age or income when guessing who takes a loan.  
Not just who they are, but what they’ve done drives outcomes
2)What someone did before with offers shapes their choices now. History of interactions stands out stronger than general traits.
3) Decisions tie closely to how people responded earlier.