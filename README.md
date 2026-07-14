# Customer Segmentation using K-Means Clustering

## Project Overview
This project uses the K-Means Clustering algorithm to segment customers of a retail store based on their Annual Income and Spending Score. The goal is to identify distinct customer groups that can help businesses understand customer behavior and make better marketing decisions.

## Dataset
- **Dataset:** Mall Customers Dataset
- **Features Used:**
  - Annual Income (k$)
  - Spending Score (1–100)

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Joblib

## Algorithm
K-Means Clustering

## Steps Performed
1. Imported the required libraries.
2. Loaded and explored the dataset.
3. Selected Annual Income and Spending Score as features.
4. Used the Elbow Method to determine the optimal number of clusters.
5. Trained the K-Means clustering model.
6. Assigned cluster labels to each customer.
7. Visualized the customer segments using a scatter plot.
8. Saved the trained model using Joblib.

## Output
- Customer clusters visualized using a scatter plot.
- Cluster centroids displayed.
- Trained model saved as `customer_segmentation_model.pkl`.

## Project Structure
```

SCT_ML_2/
├── Mall_Customers.csv
├── customer_segmentation.ipynb
├── customer_segmentation_model.pkl
└── README.md

```

## Author
**Swetha Rachakonda**