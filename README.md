# Customer-Segmentation-and-Anomaly-Detection-Using-Clustering-PCA


This project demonstrates customer segmentation and anomaly detection on credit card data using unsupervised machine learning techniques. It employs various clustering algorithms (K-Means, DBSCAN, Gaussian Mixture, Hierarchical Clustering) combined with PCA for dimensionality reduction and visualisation, and uses anomaly detection models to identify outlier behaviours.

Overview

Objective:
Segment customers based on transaction data and identify potential anomalies for further analysis.
Techniques:
Data Preprocessing (Log Transformation, Feature Scaling)
Dimensionality Reduction (PCA)
Clustering (K-Means, DBSCAN, Gaussian Mixture, Agglomerative Clustering)
Anomaly Detection (Isolation Forest, Local Outlier Factor)
Visualisation (Count Plots, Scatter Plots, Pairplots)
Dataset:
CC GENERAL.csv – A dataset containing credit card customer information.
Installation

Clone the Repository:
git clone https://github.com/yourusername/customer-segmentation.git
cd customer-segmentation
Install Required Libraries:
pip install pandas numpy matplotlib seaborn scikit-learn optuna
Usage

Place the CC GENERAL.csv file in the appropriate directory.
Run the main script:
python main.py
The script will perform data preprocessing, apply PCA, evaluate multiple clustering models, perform anomaly detection, and visualise the results through various plots.
Project Structure

customer-segmentation/
│
├── README.md            # Project documentation
├── main.py              # Main script containing the project code
├── CC GENERAL.csv       # Dataset file (ensure this file is available)
└── requirements.txt     # List of required Python packages
Results

Clustering:
Identifies optimal clusters using silhouette scores and Davies-Bouldin scores.
Anomaly Detection:
Flags unusual customer behaviour through Isolation Forest and Local Outlier Factor methods.
Visualisation:
Generates plots to display cluster distributions, PCA-reduced data, and pairplots for cluster separation.
