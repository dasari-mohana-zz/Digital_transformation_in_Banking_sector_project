# Digital_transformation_in_Banking_sector

# BUSINESS OBJECTIVE:

A Bank has a growing customer base where the majority of them are liability customers (depositors) vs. borrowers (asset customers). The bank is interested in expanding the borrowers base rapidly to bring in more business via loan interests.

A campaign that the bank ran in the last quarter showed an average single-digit conversion rate. In the last town hall, the marketing head mentioned that digital transformation being the core strength of the business strategy, how to devise effective campaigns with better target marketing to increase the conversion ratio to double-digit with same budget as per the last campaign.

# PROJECT OBJECTIVE :
To Build a Machine learning model to perform focused digital marketing by predicting the potential customers who will convert from liability customers to asset customers.


# DATA DESCRIPTION:

The data consists of the following attributes:
1. ID: Customer ID
2. Age Customer’s approximate age.
3. CustomerSince: Customer of the bank since. [unit is masked]
4. HighestSpend: Customer’s highest spend so far in one transaction. [unit is masked]
5. ZipCode: Customer’s zip code.
6. HiddenScore: A score associated to the customer which is masked by the bank as an IP.
7. MonthlyAverageSpend: Customer’s monthly average spend so far. [unit is masked]
8. Level: A level associated to the customer which is masked by the bank as an IP.
9. Mortgage: Customer’s mortgage. [unit is masked]
10. Security: Customer’s security asset with the bank. [unit is masked]
11. FixedDepositAccount: Customer’s fixed deposit account with the bank. [unit is masked]
12. InternetBanking: if the customer uses internet banking.
13. CreditCard: if the customer uses bank’s credit card.
14. LoanOnCard: if the customer has a loan on credit card.

# MY APPROCH:

1.  Importing the required libraries and reading the dataset.

      a.  Merging of the two datasets

      b.  Understanding the dataset

2.  Exploratory Data Analysis (EDA) –

      a.  Data Visualization

3.  Feature Engineering

      a.  Dropping of unwanted columns

      b.  Removal of null values

      c.  Checking for multi-collinearity and removal of highly correlated features

4.  Model Building

      a.  Performing train test split

      b.  Logistic Regression Model

      c.  Weighted Logistic Regression Model

      d.  Naive Bayes Model

      e.  Support Vector Machine Model

      f.  Decision Tree Classifier

      g.  Random Forest Classifier

5.  Model Validation

      a.  Accuracy score

      b.  Confusion matrix

      c.  Area Under Curve (AUC)

      d.  Recall score

      e.  Precision score

      f.  F1-score

6.  Handling the unbalanced data using imblearn.

7.  Hyperparameter Tuning (GridSearchCV)

      a.  For Random Forest Classifier Model

8.  Creating the final model and making predictions

9.  Saving the model with the highest accuracy in the form of a pickle file.

10. Conclusion
