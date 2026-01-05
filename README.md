🧪 Customer Segmentation Using k-Means Clustering
📌 Project Overview

Customer segmentation is a critical business strategy used to understand customer behavior and target them effectively.
In this project, I implemented k-Means clustering, an unsupervised machine learning algorithm, to group mall customers based on their annual income and spending behavior.

This project demonstrates how unsupervised learning works in real-world business scenarios where no labeled data is available.

🎯 Objectives

Understand and apply unsupervised learning

Segment customers into meaningful groups

Choose the optimal number of clusters using the Elbow Method

Visualize customer segments clearly

Interpret clusters from a business perspective

📂 Dataset Information

Dataset Name: Mall Customer Segmentation Data
Source: Kaggle

📊 Dataset Columns
Column Name	Description
CustomerID	Unique customer identifier
Gender	Male / Female
Age	Age of customer
Annual Income (k$)	Yearly income
Spending Score (1–100)	Spending behavior score
📌 Features Used for Clustering

Annual Income (k$)

Spending Score (1–100)

These features best represent customer purchasing behavior.

🧠 Problem Statement

“Group mall customers into different segments based on their income and spending habits so businesses can design better marketing strategies.”

🛠️ Tech Stack & Libraries

Python

Pandas – Data handling

NumPy – Numerical operations

Matplotlib & Seaborn – Data visualization

Scikit-learn – Machine learning algorithms

🚀 Project Implementation Steps
1️⃣ Data Loading

Loaded the dataset using Pandas

Verified data using .head()

2️⃣ Exploratory Data Analysis (EDA)

Checked data types and missing values

Analyzed statistical distribution using .describe()

3️⃣ Feature Selection

Selected only relevant numerical features

Removed IDs and categorical columns

4️⃣ Feature Scaling

Applied StandardScaler

Ensured equal importance of all features

Essential for distance-based algorithms like k-Means

5️⃣ Choosing Optimal k (Elbow Method)

Calculated WCSS (Within-Cluster Sum of Squares)

Plotted WCSS vs number of clusters

Identified the elbow point

Selected k = 5

6️⃣ Model Training

Trained k-Means model using the optimal k

Generated cluster labels for each customer

7️⃣ Cluster Visualization

Visualized clusters using scatter plots

Different colors represent different customer segments

8️⃣ Cluster Interpretation

Translated numerical clusters into meaningful business insights

📊 Cluster Interpretation (Business Insights)
Cluster	Description
Cluster 0	High income, high spending (VIP customers)
Cluster 1	Low income, low spending
Cluster 2	High income, low spending (careful customers)
Cluster 3	Low income, high spending (impulsive buyers)
Cluster 4	Average income and spending

📌 These insights help businesses:

Target promotions

Improve customer retention

Design personalized marketing strategies

📈 Results & Insights

Successfully segmented customers into 5 meaningful groups

Clear visual separation of customer behavior

Demonstrated strong understanding of unsupervised ML workflow

Converted raw data into actionable business insights
