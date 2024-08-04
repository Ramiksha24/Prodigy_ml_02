# Customer Segmentation using K-means Clustering

This project uses K-means clustering to group customers of a retail store based on their purchase history.

## Project Description

The goal of this project is to apply K-means clustering on a dataset of customer purchase history to identify distinct customer segments. This can help in understanding customer behavior and tailoring marketing strategies accordingly.

## Files

### Data

- `Mall_Customers.csv`: The dataset used for clustering.

### Notebooks

- `CustomerSegmentation.ipynb`: Jupyter Notebook containing the code for data preprocessing, K-means clustering, and visualization.

### Model

- `kmeans_model.pkl`: The saved K-means model.

### Results

- `clustered_customers.csv`: The dataset with cluster labels assigned to each customer.

## How to Run

1. **Download the dataset** from Kaggle and place it in your working directory.
2. **Open the Jupyter Notebook** `CustomerSegmentation.ipynb` located at `C:\Users\Ramiksha C Shetty\Desktop\ml_02\CustomerSegmentation.ipynb`.
3. **Run all cells** to execute the data preprocessing, clustering, and visualization steps.
4. **Save the model** and the clustered data by running the provided code.

## Requirements

The following Python libraries are required to run the notebooks:

- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- joblib

You can install these libraries using `pip`:

```sh
pip install pandas numpy scikit-learn matplotlib seaborn joblib
## Interpretation of Clusters

- **Cluster 0**: Customers with high annual income but low spending scores. These customers may be less interested in spending despite having a high income.
- **Cluster 1**: Customers with average annual income and average spending scores. They represent a balanced group of spenders.
- **Cluster 2**: Customers with low annual income and low spending scores. These customers are likely more price-sensitive.
- **Cluster 3**: Customers with low annual income but high spending scores. These customers might be the most enthusiastic shoppers despite having a lower income.
- **Cluster 4**: Customers with high annual income and high spending scores. These are the premium customers who spend the most.

Understanding these clusters can help in creating targeted marketing strategies for each group.
