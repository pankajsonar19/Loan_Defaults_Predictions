# Loan_Defaults_Predictions
My task here is to predict the probability of default for new loan applications with a reasonable degree of accuracy based on the given data of loan application of Bank XYZ over a period of time.

Inorder to achieve that, I need to train my ML algorithm on given dataset and train a model based on mapping of input features and target output, which in my case is

(1 - client with payment difficulties: he/she had late payment more than X days on at least one of the first Y installments of the loan in our sample, 0 - all other cases).

One thing needs to be clear before I proceed ahead is that my problem statement is a Classification problem, where given training sample I will tune my model to test on unknown samples.
