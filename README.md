# **Customer Segmentation Using RFM Analysis**

## **Project Overview**
This project involves analyzing transactional data from a UK-based online retail business, covering all transactions occurring between **01/12/2010 and 09/12/2011**. 

The primary objective is to segment customers using the **Recency, Frequency, and Monetary (RFM)** model, a popular framework for understanding customer behavior and enhancing marketing strategies through personalized efforts.


## **Dataset**
The dataset contains key information, including:
- **InvoiceNo**: Unique identifier for each transaction.
- **StockCode**: Product identifier.
- **Description**: Product details.
- **Quantity**: Number of products sold per transaction.
- **InvoiceDate**: Date and time of each transaction.
- **UnitPrice**: Price per unit of product.
- **CustomerID**: Unique customer identifier.
- **Country**: Customer's country of residence.


## **Approach**

### 1. **Data Understanding**
- Explored the dataset to comprehend its structure and identify key variables.
- Reviewed statistical summaries to assess the dataset's quality and completeness.

### 2. **Data Cleaning**
- Handled missing values and duplicate entries.
- Removed invalid or irrelevant transactions, such as cancellations.
- Standardized data types for consistency.

### 3. **Data Preparation**
- Computed additional metrics, such as the **TotalPrice** (Quantity × UnitPrice).
- Extracted recency, frequency, and monetary values for each customer.

### 4. **Customer Segmentation Modeling**
- Applied the **RFM framework**:
  - **Recency**: Days since the last purchase.
  - **Frequency**: Number of transactions.
  - **Monetary**: Total spending.
- Used **K-Means Clustering** to segment customers into distinct groups based on their RFM scores.
- Evaluated the optimal number of clusters using methods like the **Elbow Curve** and **Silhouette Analysis**.

### 5. **Insights and Recommendations**
- Interpreted each customer cluster based on its behavior patterns.
- Provided actionable strategies tailored to each segment to improve engagement, retention, and revenue.


## **Insights**
- Identified distinct customer segments, such as **high-value loyal customers**, **cost-conscious frequent shoppers**, and **dormant customers**.
- Highlighted patterns in customer purchasing behavior and their impact on overall business performance.


## **Recommendations**
- **Retain loyal customers** through premium loyalty programs, personalized offers, and exclusive deals.
- **Re-engage dormant customers** with targeted win-back campaigns and discounts.
- **Upsell and cross-sell** products to frequent shoppers to enhance their spending potential.
- Focus on improving **customer lifetime value (CLV)** by transitioning lower-value segments into higher-value clusters.


## **Tools and Technologies**
- **Programming Languages**: Python
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- **Clustering Algorithms**: K-Means
- **Evaluation Metrics**: Silhouette Score, Elbow Method
