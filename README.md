# Credit-Default-Prediction
This repository explain how to building credit default predicition model by using python, model can help provide insight in order to make decisions in overcoming credit default such as early risk mitigation
## Steps
1. Data understanding
2. Data cleansing
3. EDA (Exploratory Data Analysis)
4. Data preprocessing
5. Modeling
6. Model interpretation
7. Business recommendation
## Summary
1. The dataset consist of 32,581 rows & 12 columns, and after cleansing the new dataset without missing value and duplicated value becomes 31,482 rows and 12 columns or 97% from original dataset. 
2. Credit default predicition model using Random Forest Classifier because it has the highest f1 score after compared to others model (Logistic Regression and Decision Tree Classifier)
3. There are top 4 feature importance (loan_percent_income, loan_int_rate, person_income and loan_grade), focus with these features because they have more contribution in model prediction compared to others features
## Business recommendation
1. Bank can focus on 3 important features when analyzing credit, these features are:
    
    a. loan/income: Bank must be more careful with customers who have a credit/income value >= 24%               
    b. interest: Bank must be more careful with customers who have interest rates >= 11%                   
    c. loangrade: Bank must be more careful with customers who have loan grades D, E, F and G

2. The Recall score of model is 72%, meaning that out of 10 customers who are default, there are 3 customers that model failed to predict. In other words, the effectiveness of the Bank's loss reserves which is formed to be able to cover credit default reaches 72% so that financial allocation arrangements become more measurable.

3. Bank can carry out risk mitigation on loss reserves formed by sharing risks with 3rd parties, namely Insurance Institutions or Credit Guarantee Institutions for the criteria of customers who tend to default.

