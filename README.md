### **Mall Customer Segmentation Analysis**

#### **Participant Details**:
- **Name**: Harshkumar Gupta  
- **Company**: CODTECH IT SOLUTIONS  
- **ID**: CT12WDZM  
- **Domain**: Data Analytics  
- **Duration**: Dec 2024 to March 2025  
- **Mentor**: NEELA SANTHOSH KUMAR  

---

#### **Objectives**:
1. To analyze mall customer data and identify distinct customer groups based on their spending behavior and demographic information.
2. To enable targeted marketing strategies by understanding customer segments.
3. To provide actionable insights to improve customer satisfaction and revenue generation.

---

#### **Technologies Used**:
- **Python Libraries**:
  - **pandas** and **NumPy** for data manipulation and analysis.
  - **matplotlib** and **seaborn** for data visualization.
  - **scikit-learn** for clustering and machine learning.

---

#### **Key Activities**:
1. **Data Loading and Preprocessing**:
   - Imported necessary libraries (e.g., pandas, NumPy, matplotlib, seaborn, sklearn).
   - Loaded the dataset containing features such as `CustomerID`, `Gender`, `Age`, `Annual Income`, and `Spending Score`.
   - Checked for missing values and ensured data consistency.

2. **Exploratory Data Analysis (EDA)**:
   - Visualized distributions of features using histograms, box plots, and pair plots.
   - Analyzed relationships between features to uncover trends in spending behavior.

3. **Clustering Using K-Means**:
   - Applied the K-Means algorithm to group customers into clusters.
   - Used the Elbow Method to determine the optimal number of clusters.
   - Evaluated and visualized the clustering results using scatter plots.

4. **Insights and Recommendations**:
   - Interpreted customer segments to identify high-value customers, cost-conscious buyers, and other patterns.
   - Suggested marketing strategies tailored to each cluster.

---

#### **Graphs and Their Explanations**:

1. **Elbow Point Graph**:
   - **Description**: This graph plots the Within-Cluster Sum of Squares (WCSS) against the number of clusters.
   - **Purpose**: Helps identify the optimal number of clusters by observing the "elbow point," where the decrease in WCSS slows down.
   - **Insights**: Guides the selection of the number of clusters for effective segmentation, balancing accuracy and simplicity.

2. **Cluster Visualization (Scatter Plot)**:
   - **Description**: Scatter plots visualize the clusters formed by K-Means using features like `Annual Income` and `Spending Score`.
   - **Purpose**: To illustrate how customers are grouped and to provide an intuitive understanding of cluster characteristics.
   - **Insights**:
     - Clusters often represent distinct customer segments, such as high-income high-spenders or low-income low-spenders.
     - These insights help businesses target specific customer needs.

3. **EDA Visualizations**:
   - **Description**: Includes histograms, pair plots, or box plots to analyze individual features and their relationships.
   - **Purpose**: To explore data distributions and detect trends or anomalies.
   - **Insights**:
     - Identified age groups, income brackets, and gender differences in spending.
     - Highlighted potential outliers in `Annual Income` or `Spending Score`.

---

