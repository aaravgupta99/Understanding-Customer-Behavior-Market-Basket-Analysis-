
# Understanding Customer Behaviour in a Grocery Store - Readme

Welcome to the Market Basket Analysis project using the Apriori algorithm with mlxtend! This project aims to analyze grocery transactions data from various countries and identify frequent itemsets, association rules, and interesting patterns in customer purchasing behavior.
## Dataset

 - [Grocery Dataset](https://www.kaggle.com/datasets/heeraldedhia/groceries-dataset)

The dataset used in this project is an Excel file obtained from Kaggle, containing grocery transactions data from the following countries:

United Kingdom, France, Australia, Netherlands, Germany, Norway, EIRE, Switzerland, Spain, Poland, Portugal, Italy, Belgium, Lithuania, Japan, Iceland, Channel Islands, Denmark, Cyprus, Sweden, Finland, Austria, Greece, Singapore, Lebanon, United Arab Emirates, Israel, Saudi Arabia, Czech Republic, Canada, Brazil, USA, European Community, Bahrain, Malta, RSA
## Exploratory Data Analysis

Before applying the Apriori algorithm, I conducted exploratory data analysis (EDA) to understand the dataset and gain insights into the top-selling products in all countries. Using the pandas and matplotlib libraries, I plotted the top ten products sold and their quantities.
## Apriori Algorithm
I performed the Apriori algorithm on the grocery transactions made in France. The Apriori algorithm is a popular method for market basket analysis, and it helps discover frequent itemsets and association rules among items purchased together. I used the mlxtend library in Python to implement the Apriori algorithm.
## Result
The Apriori algorithm provided us with frequent itemsets and association rules based on the transactions in France. These results are essential in understanding which items are frequently bought together, enabling us to make informed decisions regarding product placement, marketing strategies, and cross-selling opportunities.
## Saving The Rules
In the final step, I saved the association rules observed in the French outlet in an Excel file for future reference and analysis.
## Future Enhancements
There are several ways to enhance this project in the future:

1. Extend the analysis to other countries in the dataset.

2. Implement other association rule mining algorithms for comparison.

3. Visualize the association rules and frequent itemsets for better understanding and presentation.

I welcome contributions and ideas from the community to expand the capabilities of this market basket analysis project.
## Getting Started
To run this project on your machine, follow these steps:

1. Download the dataset from https://www.kaggle.com/datasets/heeraldedhia/groceries-dataset.

2. Install the required Python libraries: pandas, matplotlib, mlxtend.

3. Execute the Python script to perform EDA and the Apriori algorithm on the French transactions.

Review the results and saved association rules in the output files.
