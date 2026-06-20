# Customer Segmentation & Insight Generation

## Project Overview

This project develops a customer segmentation framework using demographic, purchasing, and campaign response data. The objective is to identify distinct customer groups and generate actionable business insights that can support targeted marketing and customer retention strategies.

## Dataset

**Dataset:** Customer Personality Analysis Dataset

**Records:** 2,240+ customers

**Features:** 40+ demographic, behavioral, and campaign-related attributes

Key variables include:

* Income
* Purchase history
* Product spending categories
* Campaign responses
* Customer demographics
* Web engagement metrics

## Methodology

### Data Preprocessing

* Handled missing values using median imputation.
* Removed non-informative features.
* Encoded categorical variables using One-Hot Encoding.

### Feature Engineering

Created additional customer attributes including:

* Age
* Total Children
* Total Spending
* Total Purchases
* Campaign Acceptance Count
* Average Spend Per Purchase
* Online Purchase Ratio
* Customer Tenure

### Dimensionality Reduction

* Standardized features using StandardScaler.
* Applied Principal Component Analysis (PCA).
* Reduced 40+ features into 2 principal components for visualization and clustering.

### Customer Segmentation

* Applied K-Means Clustering.
* Used the Elbow Method to determine the optimal number of clusters.
* Identified 4 distinct customer segments.

## Results

| Segment                  | Characteristics                                   |
| ------------------------ | ------------------------------------------------- |
| Premium Customers        | Highest income, spending, and campaign engagement |
| Loyal Customers          | Consistent purchases and strong customer value    |
| Occasional Customers     | Moderate spending and engagement                  |
| Low Engagement Customers | Low spending and limited interaction              |

### Key Findings

* Processed 2,240+ customer records.
* Engineered 30+ customer behavioral features.
* Reduced 40+ dimensions into 2 principal components using PCA.
* Identified 4 customer segments through K-Means clustering.
* Generated targeted business recommendations for each segment.

## Model Evaluation

- Optimal Clusters Identified: 4
- Silhouette Score: 0.416
- PCA Components: 2

## Business Recommendations

### Premium Customers

* VIP memberships
* Exclusive promotions
* Premium product recommendations

### Loyal Customers

* Loyalty rewards programs
* Subscription benefits
* Personalized retention campaigns

### Occasional Customers

* Seasonal promotions
* Targeted marketing campaigns

### Low Engagement Customers

* Introductory discounts
* Re-engagement strategies
* Customer awareness campaigns

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* PCA
* K-Means Clustering

## Project Structure

```text
Customer-Segmentation-Insight-Generation/
│
├── data/
├── notebooks/
├── outputs/
├── README.md
├── requirements.txt
└── .gitignore
```

## Visualizations

### PCA Distribution

![PCA Plot](assets/pca_plot.png)

### Elbow Method

![Elbow Method](assets/elbow_method.png)

### Customer Segmentation

![Customer Segmentation](assets/customer_segments.png)

## Conclusion

This project successfully segmented customers into four distinct groups using PCA and K-Means clustering. The resulting customer profiles provide actionable insights that can help businesses improve customer engagement, optimize marketing strategies, and enhance overall business performance.

