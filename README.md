# Credit-Risk-Clustering

## Background
Machine Learning techniques can be used to find patterns in data and cluster accordingly. 
For example, a lending insitution can use clustering to determine which borrowers are more likely to default or miss payments. 
This allows for better returns and reduses risk.

## Setup
Synthetic data was used to replicate the lending use case containing:
- loan size
- interest rate
- borrower income
- debt to income
- number of accounts
- derogatory marks
- total debt

The data was normalized so that scalar distortions to variance could be minimized. 
Then it was fed into a logisitc regression model which can be used to determine a binary good loan - bad loan classification.

## Results

![image](https://github.com/user-attachments/assets/b5bd2371-c260-4764-8134-2a6bd31fcb26)

All healthy loans were predcted accurately but risky loans are by nature harderr to predict.
While recall is higher than precision, the precision might be more impotant for a lending institution since it is interested in minimizing losses or "negatives".

The model preformed quite well overall, although it might be interesting to see how a neural network would preform on the data. Neural networks are generally able to reveal patterns that a single functional model might miss.
