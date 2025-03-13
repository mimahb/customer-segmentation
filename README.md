# customer-segmentation
This project applies K-Means Clustering and Principal Component Analysis (PCA) to segment customers based on their purchasing behavior. By analyzing wholesale customer data, we group similar customers to help businesses understand different buying patterns and optimize marketing strategies.

## Dataset

### Source: Wholesale customers dataset

### Features:

Fresh

Milk

Grocery

Frozen

Detergents_Paper

Delicatessen

Channel (Dropped before clustering)

#### Target: Unsupervised learning (no labeled target variable)

#### Technologies Used

 Python

Pandas, NumPy (Data manipulation)

Scikit-learn (Machine learning & PCA)

Matplotlib, Seaborn (Data visualization)

### Steps in the Project

Data Preprocessing

Handle missing values (if any)

Standardize features using StandardScaler

Finding Optimal Clusters

Use Elbow Method (Inertia) to determine the best k

Use Silhouette Score to validate clustering quality

Applying K-Means Clustering

Fit K-Means with the optimal k

Assign cluster labels to each customer

Dimensionality Reduction with PCA

Reduce high-dimensional data for visualization

Plot customer clusters in 2D using PCA components

Visualization & Interpretation

Cluster distribution

PCA biplots for insights

### Results & Insights

Customers are grouped based on spending habits.

PCA helps in visualizing clusters effectively.

Businesses can target different segments for personalized marketing.

### Future Improvements

Try different clustering techniques (DBSCAN, Hierarchical Clustering).

Apply deeper customer analysis using demographic data.

Build a simple dashboard for interactive analysis.
