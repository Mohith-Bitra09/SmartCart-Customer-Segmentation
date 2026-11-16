# SmartCart – Customer Segmentation

## Overview

SmartCart is a customer segmentation project that uses machine learning to understand customer behaviour and identify groups of customers with similar characteristics.

The goal is to explore customer data, identify meaningful patterns, and group customers based on factors such as income, spending habits, and household information.

## Project Workflow

The project follows these steps:

1. **Data Loading:** Load the customer dataset and explore its structure.
2. **Data Cleaning:** Handle missing values and remove records with extreme age and income values.
3. **Feature Engineering:** Create useful features such as Age, Customer Tenure, Total Spending, and Total Children.
4. **Data Preprocessing:** Encode categorical features and scale the data.
5. **Dimensionality Reduction:** Apply PCA to reduce the data to three principal components.
6. **Finding Optimal Clusters:** Use the Elbow Method to identify the suitable number of clusters.
7. **Customer Segmentation:** Apply K-Means and Agglomerative Clustering with four clusters.
8. **Cluster Analysis:** Compare the resulting customer groups and study their characteristics.

## Machine Learning Techniques

- K-Means Clustering
- Agglomerative Clustering
- Principal Component Analysis (PCA)
- One-Hot Encoding
- StandardScaler

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Kneed
- Jupyter Notebook

## Project Structure

```text
SmartCart-Customer-Segmentation/
│
├── smartcart.ipynb
├── README.md
├── req.txt
└── .gitignore
```

## How to Run

1. Clone this repository:

```bash
git clone https://github.com/Mohith-Bitra09/SmartCart-Customer-Segmentation.git
```

2. Move into the project directory:

```bash
cd SmartCart-Customer-Segmentation
```

3. Install the required libraries:

```bash
pip install -r req.txt
```

4. Place the dataset named `smartcart_customers.csv` in the project directory.

5. Open and run the notebook:

```bash
jupyter notebook
```

## Note

The original customer dataset is not included in this repository. You need to provide the dataset separately to run the notebook.

## What I Learned

Through this project, I gained practical experience in data preprocessing, feature engineering, dimensionality reduction, and unsupervised machine learning. I also learned how to apply clustering algorithms and analyse the characteristics of different customer segments.

---

**Author:** Mohith Bitra  
**GitHub:** [Mohith-Bitra09](https://github.com/Mohith-Bitra09)