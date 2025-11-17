📌 CUSTOMER SEGMENTATION USING K-MEANS 
📝 PROJECT OVERVIEW

This project performs CUSTOMER SEGMENTATION for iFood customers using the K-MEANS CLUSTERING ALGORITHM.
The goal is to group customers based on:

SPENDING BEHAVIOR

PURCHASE FREQUENCY

INCOME

RECENCY

PRODUCT CATEGORY SPENDINGS

This segmentation helps in TARGETED MARKETING and PERSONALIZED RECOMMENDATIONS.

🛠 TOOLS & TECHNOLOGIES USED

PYTHON

PANDAS

NUMPY

SCIKIT-LEARN (STANDARD SCALER, K-MEANS, PCA)

MATPLOTLIB

SEABORN

GOOGLE COLAB

📊 STEPS PERFORMED
1️⃣ DATA LOADING

Loaded the iFood customer dataset

Displayed initial rows using df.head()

2️⃣ DATA CLEANING & PREPROCESSING

Checked missing values

Selected important numerical features

Standardized data using STANDARD SCALER

3️⃣ ELBOW METHOD

Identified the optimal number of clusters (K=4)

Used WCSS plot (Elbow graph)

4️⃣ APPLYING K-MEANS CLUSTERING

Applied K=4 clusters

Added Cluster column to dataframe

5️⃣ DIMENSIONALITY REDUCTION (PCA)

Reduced features to 2 Principal Components

Plotted PCA scatter plot for cluster visualization

6️⃣ CLUSTER INTERPRETATION

Analyzed spending patterns

Profiled each customer segment

🎯 CLUSTER INSIGHTS
CLUSTER 0 – HIGH INCOME, HIGH SPENDING (PREMIUM CUSTOMERS)

Spend more on wines, meat, fish, sweets

Good potential for premium offers

CLUSTER 1 – LOW INCOME, LOW SPENDING (BUDGET SEGMENT)

Low purchasing power

Mostly cost-sensitive customers

CLUSTER 2 – HIGH WEB PURCHASES, MEDIUM SPENDING (ONLINE SHOPPERS)

Prefer online channels

Good for digital marketing campaigns

CLUSTER 3 – HIGH STORE PURCHASES, LOW RECENCY (LOYAL CUSTOMERS)

Often purchase in-store

Recently inactive → need retention strategy

🧠 RECOMMENDATIONS

CLUSTER 0: Promote PREMIUM OFFERS and exclusive deals

CLUSTER 1: Provide DISCOUNTS, COMBO DEALS, and budget options

CLUSTER 2: Increase ONLINE ADS, personalized digital offers

CLUSTER 3: Introduce LOYALTY REWARDS, re-engagement campaigns

📁 FILES INCLUDED

customer_segmentation_kmeans.ipynb

ifood_df.csv (optional)

pca_clusters.png (optional)

👤 COMPLETED BY:

G. PRIYADHARSHINI
OASIS INFOBYTE – DATA ANALYTICS INTERN
