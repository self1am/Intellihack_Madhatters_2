# Intellihack_Madhatters_2

# Customer Segmentation Analysis

This repository contains a customer segmentation analysis using the K-Means clustering algorithm, which groups customers based on their behaviors, such as total purchases, average cart value, time spent, and other metrics. The analysis is performed on a customer behavior dataset, which is processed and visualized to generate insights for targeted marketing strategies.

## Project Overview

The goal of this project is to segment customers into distinct groups using unsupervised learning techniques. By applying K-Means clustering, we identify three customer segments that provide valuable insights for marketing optimization.

## Requirements

The following Python packages are required to run the analysis:

- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

To install the necessary libraries, you can run the following command:

```bash
pip install pandas scikit-learn matplotlib seaborn numpy
```

## Dataset

The dataset `customer_behavior_analytics.csv` contains the following columns:

- `customer_id`: Unique identifier for each customer
- `total_purchases`: Total number of purchases made by the customer
- `avg_cart_value`: The average value of the customer's cart
- `total_time_spent`: Total time spent by the customer on the platform
- `product_click`: Number of product clicks
- `discount_counts`: Number of discounts used by the customer

## Steps and Key Concepts

1. **Data Preprocessing:**
   - Handling missing values by filling them with the median of each column.
   - Scaling the numerical columns using `StandardScaler` for normalization to ensure equal importance during clustering.

2. **Customer Segmentation with K-Means:**
   - We applied K-Means clustering to segment the customers into three clusters.
   - Silhouette Score and Inertia were calculated to assess the quality of the clustering.

3. **Principal Component Analysis (PCA):**
   - PCA was applied to reduce the dimensionality of the data to two principal components, which were then visualized for better interpretation.

4. **Cluster Analysis:**
   - The customer segments were analyzed by their means across different numerical features, providing actionable insights for marketing strategies.

## Visualizations

1. **Customer Segmentation:**
   - A scatter plot showing the segmentation of customers based on `total_purchases` and `avg_cart_value`.
   

2. **PCA Visualization of Clusters:**
   - A 2D scatter plot visualizing the customer segments using PCA to reduce the feature space to two principal components.
   

## Marketing Strategies for Each Segment

- **Bargain Hunters:**  
  Offer personalized discounts and exclusive deals based on browsing and purchasing patterns.

- **High Spenders:**  
  Provide premium memberships, loyalty programs, and exclusive access to special offers.

- **Window Shoppers:**  
  Engage with personalized content and product recommendations to convert them into active buyers.

## Future Improvements

- Explore additional features, such as browsing patterns and session duration, to deepen segmentation insights.
- Experiment with other clustering methods like hierarchical clustering or DBSCAN to improve segmentation accuracy and flexibility.

## Running the Analysis

1. Install the required libraries:

   ```bash
   pip install pandas scikit-learn matplotlib seaborn
   ```

2. Load the dataset `customer_behavior_analytics.csv`.
3. Run the Python script to perform the analysis, generate visualizations, and output customer segmentations.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.




