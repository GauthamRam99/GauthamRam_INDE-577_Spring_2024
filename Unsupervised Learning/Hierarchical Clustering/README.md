# Hierarchical Clustering with Credit Card Information Dataset

This repository contains an implementation and explanation of Hierarchical Clustering applied to a dataset containing customer credit card details.

## Overview

Hierarchical Clustering is an unsupervised learning algorithm used to group similar data points into clusters. It builds a tree-like hierarchical representation of the data by recursively merging or splitting clusters based on their similarity. Hierarchical Clustering does not require a pre-defined number of clusters and can reveal the underlying structure of the data in a hierarchical manner.

## Dataset

The dataset used for Hierarchical Clustering contains customer credit card details, including various features related to credit card usage and customer demographics. Here are some details about the dataset:

- **Number of Instances**: 8950
- **Features**: The dataset consists of several features related to customer credit card usage, such as:
  - CUST_ID: Customer ID
  - BALANCE: Current balance on the credit card
  - BALANCE_FREQUENCY: Frequency of updating the balance
  - PURCHASES: Total amount of purchases made
  - ONEOFF_PURCHASES: Total amount of one-off purchases made
  - INSTALLMENTS: Total amount of purchases made in installments

### About this File


## Implementation

The Hierarchical Clustering implementation in this repository includes:

- Loading the credit card information dataset
- Preprocessing the data (e.g., handling missing values, scaling features)
- Implementing Hierarchical Clustering algorithm
- Visualizing the clustering results
- Analyzing and interpreting the clusters

## Dependencies

To run the implementation, you'll need the following dependencies:

- Python 3.x
- Machine learning libraries (e.g., NumPy, Pandas, Scikit-learn)
- Data visualization libraries (e.g., Matplotlib, Seaborn)

## Author

This repository is authored and maintained by Gautham Ram. If you have any questions, suggestions, or contributions, feel free to reach out.
