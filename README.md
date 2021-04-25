# LendingClub_Analysis

#### Lending Club is a marketplace for personal loans that matches borrowers who are seeking a loan with investors looking to lend money and make a return. Each borrower fills out a comprehensive application, providing (income, employment length, debt-to-income ratio, etc.) Lending Club evaluates each borrower’s FICO score(credit score) using past historical data (and their own data science process!) and assigns an interest rate to the borrower.

#### Approved loans are listed on the Lending Club website, where qualified investors can browse recently approved loans, the borrower’s credit score, the purpose for the loan, and other information from the application.

#### Once an investor decides to fund a loan, the borrower then makes monthly payments back to Lending Club. Lending Club redistributes these payments to investors. This means that investors don’t have to wait until the full amount is paid off to start to see returns. If a loan is fully paid off on time, the investors make a return which corresponds to the interest rate the borrower had to pay in addition to the requested amount.

#### Many loans aren’t completely paid off on time, however, and some borrowers default on the loan. That’s the problem we’ll be trying to address as we clean some data from Lending Club for machine learning. Let’s imagine we’ve been tasked with building a model to predict whether borrowers are likely to pay or default on their loans.

#### I have done Data Cleaning, univariate bivariate and build Classification model like Logistic Regression, Decision Tree,Random Forest, XG Boost, SGD Boost.  

#### Logistic regression performed the best, did Hyperparameter tuning and found best parameter.

### Conclusion
#### Total bank card limit and installment play a major role in predicting if some one is going to default or not, which means that a person with higher installment is more likely to default which can be quite obvious that that applicant is not able to manage his income in order to pay back the loan.
#### Similarly a person having higher bank card limit is less likely to default.
#### Home owenership also plays a major role in predicting default.
#### Total credit accounts, which as we stated in EDA, means that person is getting thismany number of accounts because he/she was in good terms with the previous creditor.
#### It is interesting to see that some regions have major play in default, which means that company have to take region into consideration while giving out loan.
