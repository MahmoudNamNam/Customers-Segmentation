# Customer Segmentation Project

## Overview

This project focuses on analyzing and segmenting customers based on their transactional behavior and demographic features. The goal is to identify distinct customer groups and provide actionable insights to improve marketing strategies, enhance customer engagement, and optimize business operations.

## Clustering Analysis

We employed clustering techniques to segment customers into distinct groups. The clustering results are summarized below:

### Cluster Distribution

- **Cluster 0**: 250 customers
- **Cluster 1**: 157 customers
- **Cluster 2**: 105 customers
- **Cluster 3**: 194 customers
- **Cluster 4**: 294 customers

### Key Metrics by Cluster

- **Transaction Count**:
  - Highest in **Cluster 0** (6.60)
  - Lowest in **Cluster 1** (2.83)

- **Coupon Usage Count**:
  - Highest in **Cluster 0** (3.25)
  - Lowest in **Cluster 2** (1.37)

- **Redemption Rate**:
  - Highest in **Cluster 3** (1.34)
  - Lowest in **Cluster 1** (0.51)

- **Recency** (Days since last transaction):
  - Highest in **Cluster 2** (420.58)
  - Lowest in **Cluster 0** (42.83)

- **Customer Tenure** (Days since first transaction):
  - Highest in **Cluster 0** (717.43)
  - Lowest in **Cluster 2** (20.53)

## Insights & Recommendations

- **High Engagement Clusters**:

  - **Clusters 0 and 3** have high transaction counts, coupon usage, and redemption rates. Focus on enhancing engagement and retention strategies for these clusters.

- **Low Engagement Clusters**:
  - **Clusters 1, 2, and 4** have lower metrics across various dimensions. Implement targeted promotions or re-engagement campaigns to improve customer activity.

- **New Customers**:
  - **Cluster 2** shows a high recency and low tenure, indicating newer customers. Develop onboarding strategies to increase their engagement and retention.

## Setup & Usage

1. **Clone the Repository**

   ```bash
   git clone https://github.com/MahmoudNamNam/Customers-Segmentation
   ```
