# Customer Segmentation Using Clustering

## Project Overview
This project focuses on segmenting customers of a mall based on their demographic and behavioral characteristics using unsupervised machine learning techniques. By identifying distinct customer segments, businesses can develop targeted marketing strategies, optimize product offerings, and enhance customer experience.

## Dataset
The analysis uses the "Mall_Customers.csv" dataset, which contains the following features:
- CustomerID: Unique identifier for each customer
- Genre: Customer gender (Male/Female)
- Age: Customer age
- Annual Income (k$): Annual income of customers in thousands of dollars
- Spending Score (1-100): Score assigned to customers based on spending behavior and frequency

## Methodology
The project follows these key steps:

1. **Data Exploration and Preprocessing**
   - Exploratory data analysis to understand the distribution of features
   - Checking for missing values and outliers
   - Feature scaling to normalize the data

2. **Customer Segmentation**
   - K-means clustering to identify natural groupings of customers
   - Determining the optimal number of clusters using the Elbow method and Silhouette score
   - Principal Component Analysis (PCA) for dimensionality reduction and visualization

3. **Segment Analysis**
   - Profiling each customer segment based on their characteristics
   - Visualizing the clusters to understand the segmentation
   - Deriving business insights from the identified segments

## Key Findings
The analysis reveals distinct customer segments with unique characteristics:
- High income, high spending customers (potential loyal customers)
- High income, low spending customers (potential targets for marketing campaigns)
- Low income, high spending customers (value-conscious customers)
- Low income, low spending customers (budget-conscious customers)
- Average income and spending customers (standard customers)

## Technologies Used
- Python for data analysis and modeling
- Libraries: NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn
- K-means clustering for customer segmentation
- Principal Component Analysis (PCA) for dimensionality reduction

## How to Use
1. Clone this repository
2. Ensure you have the required Python libraries installed
3. Run the Jupyter notebook `Customer_Segmentation_Using_Clustering.ipynb`
4. Follow the analysis and explore the customer segments

## Business Applications
The identified customer segments can be used for:
- Targeted marketing campaigns
- Personalized product recommendations
- Customer retention strategies
- Store layout optimization
- Inventory management based on customer preferences

## Future Work
- Incorporate additional customer data such as purchase history and product preferences
- Experiment with other clustering algorithms (DBSCAN, Hierarchical Clustering)
- Develop a recommendation system based on the identified segments
- Implement real-time customer segmentation for dynamic marketing

## Conclusion
Customer segmentation provides valuable insights into different customer groups, enabling businesses to tailor their strategies to meet specific customer needs. This project demonstrates how machine learning techniques can be applied to identify meaningful customer segments based on demographic and behavioral data.

## Author
Tahir Ali

## Contribution
This project is open-source and available for educational and research purposes. Feel free to use and modify the code with proper attribution.
