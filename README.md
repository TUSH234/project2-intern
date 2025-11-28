📊 Customer Segmentation using K-Means & PCA

A complete machine-learning project that performs data collection, cleaning, EDA, clustering, visualization, and customer profiling using K-Means and PCA.

🚀 Project Overview

Customer segmentation helps businesses understand different groups of customers based on their behaviour and characteristics.
In this project, we:

* Collected and cleaned customer data

* Performed Exploratory Data Analysis (EDA)

* Visualized distributions such as Age, Income, Gender Count, etc.

* Scaled the dataset

* Used Elbow Method & Silhouette Score to find optimal clusters

* Applied K-Means clustering

* Used PCA for dimensionality reduction and cluster visualization

* Performed Cluster Profiling

* Exported final results to a CSV file

* Created a professional report and PPT presentation
  

🧩 Project Workflow

1️⃣ Data Collection

Imported customer dataset (CSV format).

Loaded and inspected dataset shape, datatypes, and null values.

2️⃣ Data Cleaning

Removed/filled missing values

Dropped duplicates

Converted categorical variables

Standardized column names

3️⃣ Exploratory Data Analysis (EDA)

* Visualizations included:

* Age distribution

* Income distribution

* Gender count

* Correlation heatmap

* Outlier analysis using boxplots

🔧 Data Preprocessing

Applied StandardScaler to scale numerical features

Encoded categorical columns if needed

Final dataset prepared for clustering

📈 Finding Optimal Number of Clusters
Elbow Method

Inertia plotted vs. number of clusters

Silhouette Score

Verified cluster consistency and separation

Outcome: Selected optimal k clusters.

🤖 K-Means Clustering

Applied K-Means using optimal value of k

Stored cluster labels in the dataset

Saved processed data as segmented_customers.csv

🎨 Dimensionality Reduction & Visualization
PCA (Principal Component Analysis)

Reduced features to 2 components

Plotted PCA scatter plot with clusters

Visualized cluster separation clearly

🔍 Cluster Profiling

For each cluster, we analyzed:

Average age

Average income

Gender distribution

Spending score (if available)

Behavioural patterns

This helps companies design targeted marketing strategies.

🛠 Tech Stack

* Python

* Pandas, NumPy

* Matplotlib, Seaborn

* Scikit-learn

* PCA

📌 Results

Successfully segmented customers into meaningful groups

Visualized clusters in 2D space using PCA

Provided insights for targeted marketing

Exported final output file for business use
