**Customer Segmentation Project**

This project performs customer segmentation using unsupervised machine learning techniques, specifically KMeans clustering, on the **Mall Customers** dataset. The goal is to segment customers based on their behavior and demographics to support targeted marketing strategies.

## 📊 Dataset

The dataset (`Mall_Customers.csv`) contains data on 200 customers, including:
- **CustomerID**
- **Gender**
- **Age**
- **Annual Income (k$)**
- **Spending Score (1-100)**

## 🧠 Objective

To identify distinct customer groups based on income and spending patterns using clustering algorithms. These segments can then be used for personalized marketing and business insights.

## 🔍 Exploratory Data Analysis (EDA)

- Distribution plots for Age, Income, and Spending Score
- Gender-based comparisons using KDE plots and boxplots
- Pair plots to visualize multivariate relationships

## 🔗 Clustering

### Univariate Clustering
- **Feature**: Annual Income
- **Model**: KMeans with 3 clusters
- **Outcome**: Customers grouped based on income levels

### Bivariate Clustering
- **Features**: Annual Income, Spending Score
- **Model**: KMeans with optimal clusters (determined via Elbow Method)
- **Outcome**: 5 distinct customer segments identified

## 📈 Insights

- Clear behavioral patterns found across income and spending levels
- Certain customer groups such as "high income, low spenders" and "low income, high spenders" were particularly notable
- These segments can inform targeted promotions and customer engagement strategies

## 🛠️ Technologies Used

- Python
- Pandas
- Matplotlib & Seaborn
- Scikit-learn

## 📁 Files

- `Customer_segmentation_project.ipynb`: Jupyter notebook with full code and analysis
- `Mall_Customers.csv`: Source data file (not included here)

## 🚀 How to Run

1. Clone this repository
2. Install required libraries (`pip install -r requirements.txt`)
3. Run the Jupyter notebook `Customer_segmentation_project.ipynb`

## 📬 Contact

For questions or collaboration, feel free to reach out!

---
