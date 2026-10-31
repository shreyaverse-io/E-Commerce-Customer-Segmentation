# 🛒 E-Commerce Customer Segmentation

## 📌 Project Overview

E-Commerce Customer Segmentation is a Machine Learning project that aims to group customers based on their purchasing behaviour using Unsupervised Learning techniques.

The project uses **RFM Analysis (Recency, Frequency, Monetary)** to understand customer purchasing patterns and applies two clustering algorithms: **K-Means and DBSCAN** to identify meaningful customer segments.

The goal is to help e-commerce businesses understand their customers, identify high-value customers, and develop effective marketing strategies.

## 🎯 Objectives

- Analyze customer purchasing behaviour using RFM analysis.
- Segment customers based on their purchasing patterns.
- Apply K-Means and DBSCAN clustering algorithms.
- Compare the performance of both clustering techniques.
- Use PCA for dimensionality reduction.
- Visualize customer clusters using t-SNE.
- Identify meaningful customer groups for business insights.

## 🛠️ Technologies & Libraries Used

| Technology | Purpose |
|---|---|
| Python | Programming language |
| Pandas | Data manipulation |
| NumPy | Numerical computations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Scikit-learn | Machine Learning algorithms |
| Google Colab / Jupyter Notebook | Development environment |

## 📊 Dataset

The project uses an E-Commerce transaction dataset containing customer purchase information.

Important attributes include:

- **CustomerID:** Unique customer identification.
- **InvoiceDate:** Date of purchase.
- **InvoiceNo:** Transaction identification.
- **Quantity:** Number of products purchased.
- **UnitPrice:** Price per product.

These attributes are used to calculate the RFM metrics.

## 🔍 Project Workflow

### 1. Data Preprocessing
- Load and understand the dataset.
- Handle missing values and duplicate records.
- Remove invalid transactions.
- Prepare the data for analysis.

### 2. RFM Analysis

RFM stands for:

- **Recency:** How recently a customer made a purchase.
- **Frequency:** How frequently a customer makes purchases.
- **Monetary:** How much money a customer spends.

RFM analysis helps understand customer purchasing behaviour.

### 3. Feature Scaling

StandardScaler is used to scale the RFM features so that all features contribute fairly to the clustering process.

### 4. K-Means Clustering

K-Means is an unsupervised learning algorithm that groups customers into a predefined number of clusters based on their similarities.

The Elbow Method and Silhouette Score can be used to determine and evaluate the clusters.

### 5. DBSCAN Clustering

DBSCAN (Density-Based Spatial Clustering of Applications with Noise) groups customers based on the density of data points.

Unlike K-Means, it does not require specifying the number of clusters in advance and can identify outliers as noise points.

### 6. PCA (Principal Component Analysis)

PCA is used for dimensionality reduction. It transforms the original features into fewer components while preserving as much important information as possible.

### 7. t-SNE Visualization

t-SNE (t-Distributed Stochastic Neighbor Embedding) helps visualize high-dimensional customer data in two dimensions to understand the distribution of different clusters.

### 8. Customer Segmentation

Based on the clustering results, customers can be categorized into groups such as:

- High-Value Customers
- Loyal Customers
- Potential Customers
- At-Risk Customers
- Low-Value Customers

## 📈 Evaluation Metrics

The following metrics and techniques can be used to evaluate clustering performance:

- **Silhouette Score:** Measures how well-separated the clusters are.
- **Inertia:** Measures the sum of squared distances from data points to their assigned cluster centers in K-Means.
- **Cluster Distribution:** Helps understand the number of customers in each cluster.
- **Noise Points:** Helps identify outliers detected by DBSCAN.

## 💡 Business Applications

Customer segmentation can help e-commerce businesses:

- Create personalized marketing campaigns.
- Identify high-value customers.
- Improve customer retention.
- Offer targeted discounts and promotions.
- Re-engage inactive customers.
- Develop better customer engagement strategies.

## 🚀 How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/shreyaverse-io/E-Commerce-Customer-Segmentation.git
```

### 2. Navigate to the Project Folder

```bash
cd E-Commerce-Customer-Segmentation
```

### 3. Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### 4. Run the Project

- Open the Jupyter Notebook or Google Colab.
- Upload the dataset.
- Open the project notebook.
- Execute the cells sequentially to perform customer segmentation.

## 🔮 Future Improvements

- Develop an interactive dashboard using Streamlit.
- Experiment with additional clustering algorithms.
- Improve customer persona identification.
- Build a personalized product recommendation system.

## 👩‍💻 Author

**Shreya Taneja**

B.Tech | Artificial Intelligence and Machine Learning

GitHub: [shreyaverse-io](https://github.com/shreyaverse-io)

---

⭐ If you find this project interesting, consider giving this repository a star!

**Made with ❤️ using Python and Machine Learning.**
