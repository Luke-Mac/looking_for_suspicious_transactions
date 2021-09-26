# looking_for_suspicious_transactions
Apply SQL skills to analyze historical credit card transactions and consumption patterns in order to identify possible fraudulent transactions.

## Task: Data Modeling
Create an entity relationship diagram (ERD) by inspecting the provided CSV files.

![QuickDBD-suspicious_transactions ERD](https://user-images.githubusercontent.com/88257254/134800618-618d7a86-7c0b-4012-9a84-8283791f7ebb.png)
![QuickDBD-suspicious_transactions](https://user-images.githubusercontent.com/88257254/134800303-d74f6214-d20e-431a-8947-e8a9a87fd41a.png)

## Task: Data Engineering

Using database model as a blueprint, I created a database schema for each table and relationships. Specifying data types, primary keys, foreign keys, and any other constraints that needed to be defined.
After creating the database schema, I imported all the data from the corresponding CSV files.

## Task: Data Analysis

Part 1:
The CFO of your firm has requested a report to help analyze potential fraudulent transactions. Using your newly created database, generate queries that will discover the information needed to answer the following questions, then use your repository's ReadME file to create a markdown report you can share with the CFO:


Some fraudsters hack a credit card by making several small transactions (generally less than $2.00), which are typically ignored by cardholders.
How can you isolate (or group) the transactions of each cardholder?



Count the transactions that are less than $2.00 per cardholder.


Is there any evidence to suggest that a credit card has been hacked? Explain your rationale.




Take your investigation a step futher by considering the time period in which potentially fraudulent transactions are made.


What are the top 100 highest transactions made between 7:00 am and 9:00 am?


Do you see any anomalous transactions that could be fraudulent?


Is there a higher number of fraudulent transactions made during this time frame versus the rest of the day?


If you answered yes to the previous question, explain why you think there might be fraudulent transactions during this time frame.




What are the top 5 merchants prone to being hacked using small transactions?


Create a view for each of your queries.
