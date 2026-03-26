Task objective:
Cluster customers based on spending habits and propose marketing strategies tailored to each
segment.

My Approach:

1)Load dataset into jupyter download from kaggle(Mall_Customers)

2)Data cleaning such as checking duplicate values and Null values

3)Exploratory Data Analysis (EDA):

Visualizing Distributions: Analyzed the distribution of Age, Income, and Spending Score using histograms and KDE plots.
Correlation Analysis: Used heatmaps to identify relationships between features (e.g., how Age affects Spending Score).

4)Data Preprocessing:

Feature Selection: Focused on Annual Income and Spending Score for precise clustering.
Feature Scaling: Applied StandardScaler to ensure all features contribute equally to the distance calculations in K-Means.

5)K-Means Clustering:

Model Training: Initialized and fitted the K-Means algorithm to the scaled data.
Evaluation: Validated cluster separation with the Silhouette Score.
Model Training: Initialized and fitted the K-Means algorithm to the scaled data.K-Means Clustering

6)Dimensionality Reduction & Visualization:
PCA (Principal Component Analysis): Reduced the data to 2 dimensions to visualize the global structure of the segments

Results and findings:
1)The "Elite" Growth Driver: This is your most lucrative segment. They're relatively young (~33 years old) with high purchasing power and engagement.
2)The "Standard" Foundation: This is your largest segment with 81 customers. It represents your "average" middle-aged shopper. It is also your most stable revenue stream, though moderate.
3)The "Careful" Paradox: This is your youngest segment (~25 years old) with the lowest purchasing power. Yet they have a very high spending score of 79.36. It appears they're very loyal to your brand or only make "treat" purchases.
4)The "Impulsive" Opportunity: Your "Impulsive" segment has the highest average income of $88.2k but also has the lowest spending score of 17.11. It appears there is a huge "experience gap" with this segment.