# RFM
RFM Analysis
RFM (Recency, Frequency, Monetary) is a very Simple Technique that we can apply it very easy and get the super useful analysis for our Customer Segmentation.
RFM considers recency, frequency and monetary values for each customer. Combines them, and then groups them into different customer segments for easy recall and campaign targeting.
We need a few details of each Customers:
Customer ID / Name / Company etc — to identify them
Recency (R) as days since last purchase: How many days ago was their last purchase? Deduct most recent purchase date from today to calculate the recency value. 1 day ago? 14 days ago? 500 days ago?
Frequency (F) as total number of transactions: How many times has the customer purchased from our store? For example, if someone placed 10 orders over a period of time, their frequency is 10.
Monetary (M) as total money spent: How many $$ (or whatever is your currency of calculation) has this customer spent? Simply total up the money from all transactions to get the M value.

Dataset: This is text file which has features Customer id,purchase amount,date of purchase.
Modelling: K means Clustering 
