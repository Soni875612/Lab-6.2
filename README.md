## Lab Activity 6.2 — Customer Segmentation Using K-Means Clustering
Objective
To perform customer segmentation using K-Means clustering based on spending patterns in an Indian retail dataset.
Dataset
🔗 Retail Sales Dataset — Kaggle
Requirements

Python (Jupyter Notebook / Google Colab)
Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn

Prerequisites

Basic Python knowledge
Understanding of clustering techniques, particularly K-Means
Familiarity with Pandas, NumPy, Matplotlib, Seaborn, and Scikit-Learn

Problem Statement
In the competitive retail market, understanding customer behavior is critical. This task segments customers based on spending patterns (annual income, spending scores) using K-Means clustering to help retailers target marketing campaigns, optimize promotions, and improve customer satisfaction.
Steps
StepTask1Import required libraries2Load the dataset3Data preprocessing — handle missing values, encode/scale features4Determine optimal number of clusters using the Elbow Method5Apply K-Means Clustering6Visualize clusters using PCA (2D scatter plot)7Interpret clusters and suggest business strategies
Key Concept — Elbow Method
The Elbow Method plots inertia (WCSS) against the number of clusters. The point where the curve bends (the "elbow") is the optimal number of clusters.
Tech Stack
LibraryUsagepandasData loading and manipulationnumpyNumerical operationsscikit-learnK-Means, PCA, preprocessingmatplotlib / seabornElbow plot and cluster visualization
File Structure
Lab6_2/
├── Lab6_2.ipynb              # Main notebook
├── retail_sales_dataset.csv  # Dataset
└── README.md                 # This file
Conclusion
K-Means clustering identifies distinct customer segments based on spending behavior. These clusters help retailers design targeted marketing strategies. Limitations include sensitivity to initial cluster centers — alternatives like Hierarchical Clustering or DBSCAN can be explored for better results.
