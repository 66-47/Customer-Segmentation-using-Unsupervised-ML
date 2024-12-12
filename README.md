# Customer Segmentation Using Unsupervised ML


## Project Overview

This project uses unsupervised machine learning techniques to generate customer insights by segmenting them based on their spending habits. By clustering customers into distinct groups, businesses can tailor strategies to improve customer engagement, retention, and sales performance.

## Tools & Technologies

### Python: Programming language for data processing and modeling.
### Jupyter Notebook: For developing, visualizing, and documenting the project.
### Pandas: For data manipulation and preprocessing.
### Unsupervised Learning: Specifically using the K-Means clustering algorithm.
### Data Analysis: To generate insights from the clustered data.

## Project Workflow

### 1. Data Cleaning & Preprocessing

#### Handling Missing Values and Duplicates:

Checked for null values and imputed or removed them as appropriate.
Identified and removed duplicate entries to ensure data integrity.

### 2. Feature Exploration
Conducted exploratory data analysis (EDA) to understand key features and their distributions.
Focused on customer transaction data to extract insights related to spending behavior.

### 3. Recency, Frequency, Monetary (RFM) Analysis

### Recency (R): Number of days since the customer's last purchase.
### Frequency (F): Total number of purchases made by the customer.
### Monetary (M): Total spending by the customer.
#### RFM values were calculated to quantify customer purchasing behavior.

### 4. Data Transformation

#### Log Transformation:
Applied log transformation to reduce skewness in the data, making it more suitable for clustering.

#### Standard Scaling:
Used StandardScaler to standardize the RFM features, ensuring they are on a comparable scale.

### 5. K-Means Clustering
Applied the K-Means clustering algorithm to segment the customers based on their RFM scores.
Determined the optimal number of clusters using the Silhouette Score, which measures how well each data point fits within its cluster.

### 6. Results & Interpretation

#### Identified three distinct customer segments:
### Major: High-value customers with frequent and recent purchases.
### Average: Moderate-value customers with regular but less frequent purchases.
### Churn: Customers who are at risk of leaving due to infrequent purchases or inactivity.

### 7. Actionable Insights

### Major Segment:
Offer loyalty rewards, exclusive discounts, and personalized recommendations to retain these high-value customers.
### Average Segment:
Provide targeted promotions and incentives to increase purchase frequency and engagement.
### Churn Segment:
Implement win-back campaigns, such as special offers or reminders, to re-engage these customers.

## Results

### Clustering Performance:
Used the Silhouette Score to validate the clustering quality, ensuring the identified segments are well-separated and meaningful.
### Segment Analysis:
Delivered clear insights into customer behavior, helping the business strategize actions for each group.

## Conclusion

This project successfully segmented customers into meaningful groups using unsupervised learning techniques. The insights derived from these clusters can help businesses optimize their marketing strategies, improve customer engagement, and boost overall profitability.

