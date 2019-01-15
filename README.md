# ubiquitous-potato
###Predicting Responses to a Marketing Offer using Amazon ML
###Used batch prediction in Amazon ML to predict subscription to a new product, called the certificate of deposit by using the dataset which contains customer information and their response to previous marketing contacts.
# Dataset obtained from UCI Machine Learning Repository. 
1) Data has been cleaned (Missing values handled, Outcome modified from 'Yes/No' to binary variables.
2) banking_training_data is the training data. Attribute y contains the binary results (0 or 1) which indicates whether the customer subscribed to the new product - Certificate of Deposit.
3) Model trained using the first 70 percent of input data for training and the last 30 percent for evaluation.
4) Model's Accuracy is measured using AUC metric.
5) Score threshold is set to 77 percent to get the top 3 percent of customers who will subscribe to the product.
6) Batch prediction is done using banking-batch.csv using the training data.
7) bp-m7a7rOLY98v-banking-batch.csv contains the predicted outcome in which the best answer of 1 indicates the top 3 percent of customers who subscribed to the product.
