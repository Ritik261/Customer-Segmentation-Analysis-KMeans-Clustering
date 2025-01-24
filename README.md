# Customer Segmentation Using K-Means

## Overview
This project demonstrates the implementation of K-Means clustering for customer segmentation. Customer segmentation helps businesses identify distinct groups within their customer base, enabling targeted marketing strategies and improved customer satisfaction.

## Objectives
The primary goals of this project were:
- To analyze customer data and group customers into distinct segments.
- To use the K-Means clustering algorithm to identify patterns and clusters in the data.
- To visualize the clusters and interpret the insights for actionable business strategies.

## Dataset
The dataset used for this project contains customer information, such as:
- **Customer ID**
- **Age**
- **Annual Income**
- **Spending Score**

### Data Source
The dataset was sourced from a publicly available repository. It contains anonymized data relevant to customer demographics and behavior.

## Tools and Technologies
- **Python**: Primary programming language.
- **Libraries Used**:
  - `pandas`: For data manipulation and preprocessing.
  - `numpy`: For numerical computations.
  - `matplotlib` and `seaborn`: For data visualization.
  - `sklearn`: For implementing the K-Means clustering algorithm.

## Methodology
1. **Data Preprocessing**:
   - Loaded the dataset and checked for missing or inconsistent values.
   - Performed feature scaling to normalize the data for better clustering performance.

2. **Exploratory Data Analysis (EDA)**:
   - Visualized key features using bar charts, histograms, and scatter plots.
   - Analyzed correlations between variables to understand data relationships.

3. **K-Means Clustering**:
   - Applied the Elbow Method to determine the optimal number of clusters.
   - Performed clustering using the `KMeans` class from the `sklearn.cluster` module.

4. **Visualization and Insights**:
   - Visualized the clusters in a 2D space for interpretability.
   - Extracted key characteristics of each cluster to define customer segments.

## Insights
- The analysis identified distinct customer groups based on their spending habits and income levels.
- Key clusters included high-income, high-spending customers and low-income, low-spending customers, among others.
- These segments can guide personalized marketing campaigns, loyalty programs, and resource allocation.

## Results
- **Optimal Clusters**: Determined using the Elbow Method.
- **Visualization**: Scatter plots highlighting clusters and their centroids.
- **Business Impact**: Enhanced understanding of customer segments for data-driven decision-making.

## How to Use
1. Clone this repository:
   ```bash
   git clone <repository-url>
   ```
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the notebook:
   ```bash
   jupyter notebook Customer_Segmentation_KMeans.ipynb
   ```

## Future Work
- Extend the analysis to include additional features such as geographic location and purchase history.
- Compare K-Means with other clustering algorithms like DBSCAN or hierarchical clustering.
- Deploy the model as a web application for real-time customer segmentation.

## Author
Ritik Singh

For any questions or suggestions, feel free to reach out at:
- Email: ritiksingh1356@gmail.com
- LinkedIn: [linkedin.com/in/ritiksingh01](https://linkedin.com/in/ritiksingh01)

