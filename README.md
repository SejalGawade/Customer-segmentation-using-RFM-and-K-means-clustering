# Customer-segmentation-using-RFM-and-K-means-clustering

This project implements customer segmentation using RFM (Recency, Frequency, Monetary) analysis combined with K-means clustering. The objective is to classify customers into distinct segments based on their purchasing behavior to help businesses make informed decisions for targeted marketing strategies and personalized customer engagement.

# Key Features 

Customer Segmentation: Cluster customers based on their RFM scores and purchasing behavior.
Behavioral Insights: Understand customer behavior by analyzing Recency, Frequency, and Monetary value of purchases.
Marketing Strategy: Use customer segments to improve marketing campaigns, promotions, and customer retention efforts.

## Procedure
# 1. Data Preprocessing, Exploratory Data Analysis (EDA), and Data Engineering
Libraries Used: Pandas, Numpy, Matplotlib, Seaborn
Steps include cleaning the dataset, handling missing values, and performing exploratory data analysis to identify key trends and distributions in customer data.

# 2. RFM Scoring
Each customer is assigned an RFM score based on:
Recency: Days since the last purchase.
Frequency: Number of purchases in a specified period.
Monetary: Total amount spent by the customer.

# 3. Model Building (K-means Clustering)
Libraries Used: Scikit-learn, Seaborn, Matplotlib

The RFM scores are used as features to perform K-means clustering, which groups customers into different clusters based on their similarity in purchasing patterns.

# 4. Cluster Evaluation and Visualization
Libraries Used: Scikit-learn, Seaborn, Matplotlib

Evaluate the clusters using **Elbow Method** and inertia to determine the optimal number of clusters. Visualize customer segments using graphs for better understanding.

# 5. Result Interpretation and Insights
Understand the purchasing behavior of each customer segment (e.g., high-value customers, frequent shoppers, low value or lost customers).
Use insights to create personalized marketing strategies and improve customer retention.

# Results
Customers are grouped into segments based on their RFM scores.
The optimal number of clusters is determined using K-means clustering.
Each segment exhibits distinct purchasing patterns, allowing for targeted marketing and better customer engagement.

# Tools and Libraries
Data Processing: Pandas, Numpy

Visualization: Matplotlib, Seaborn

Clustering: Scikit-learn
