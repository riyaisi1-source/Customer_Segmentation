Instacart Market Basket Analysis 🛒

This repository walks through the Instacart Market Basket Analysis problem using a series of Jupyter Notebooks. The data is a large, relational set of files capturing customer orders over time — anonymized and drawn from a sample of over 3 million grocery orders placed by 200,000+ Instacart shoppers.

The goal is to understand and predict what a customer is likely to order next, based on their past purchases and shopping habits.

📁 Notebooks
Data Exploration
Digs into and visualizes the raw data.
Looks at how often products are bought, how reorder patterns behave, and how ordering shifts over time.
Customer Segmentation
Uses Principal Component Analysis (PCA) to reduce dimensionality of purchasing behavior across aisles.
Applies K-Means Clustering to group users into segments based on what they tend to buy.
Association Rule Mining
Applies the Apriori algorithm to uncover association rules between products.
Surfaces frequently co-purchased items and product combinations.
📊 About the Dataset

For every user, the data includes:

4 to 100 past orders
The sequence of products within each order
The day of week and hour each order was placed
The time gap between one order and the next

Because the data is both structured and time-aware, it opens the door to deeper analysis of customer behavior and buying preferences.

Explore the notebooks to see how these different techniques come together to analyze real-world retail data.
