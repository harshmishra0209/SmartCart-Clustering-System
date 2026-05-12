# 🛒 SmartCart Customer Segmentation System

An end-to-end Machine Learning project that performs **Customer Segmentation using Clustering Algorithms** on SmartCart customer data.
This project helps businesses understand customer behavior, spending habits, income groups, 
and purchasing patterns to improve marketing strategies and customer targeting.

---

# 🚀 Project Overview

Customer segmentation is one of the most important applications of Machine Learning in the retail industry.

In this project:

* Customer data is cleaned and preprocessed
* Feature engineering is performed
* Outliers are removed
* Data is transformed using PCA
* Multiple clustering techniques are applied
* Customer groups are visualized and analyzed

The final result helps identify different types of customers based on:

* Income
* Spending habits
* Family structure
* Age
* Product purchasing behavior
* Customer tenure

---

# 📌 Problem Statement

Retail companies often struggle to:

* Identify valuable customers
* Understand spending behavior
* Create personalized marketing campaigns
* Improve customer retention

This project solves the problem by grouping similar customers into clusters using unsupervised learning techniques.

---

# 🧠 Machine Learning Concepts Used

* Data Cleaning
* Feature Engineering
* One Hot Encoding
* Standard Scaling
* Principal Component Analysis (PCA)
* K-Means Clustering
* Agglomerative Clustering
* Elbow Method
* Silhouette Score
* Data Visualization

---

# 📂 Dataset Information

The dataset contains customer information such as:

| Feature            | Description                    |
| ------------------ | ------------------------------ |
| Income             | Customer yearly income         |
| Education          | Education qualification        |
| Marital_Status     | Relationship status            |
| Kidhome / Teenhome | Number of children             |
| MntWines           | Amount spent on wine           |
| MntFruits          | Amount spent on fruits         |
| MntMeatProducts    | Amount spent on meat products  |
| MntFishProducts    | Amount spent on fish products  |
| MntSweetProducts   | Amount spent on sweets         |
| MntGoldProds       | Amount spent on gold products  |
| Dt_Customer        | Customer enrollment date       |
| Recency            | Recent interaction information |
| Response           | Campaign response              |

---

# ⚙️ Workflow

## 1️⃣ Data Preprocessing

Performed the following preprocessing steps:

* Missing value handling
* Median imputation for Income
* Date conversion
* Feature creation
* Outlier removal
* Correlation analysis

### Feature Engineering

Created new useful features:

```python
Age = 2026 - Year_Birth
Customer_Tenure_Days
Total_spending
Total_Children
```

---

## 2️⃣ Data Cleaning

Removed:

* Unnecessary columns
* Extreme age values
* Extremely high income outliers

This improved clustering quality significantly.

---

## 3️⃣ Encoding Categorical Data

Used:

```python
OneHotEncoder
```

Encoded columns:

* Education
* Living_with

---

## 4️⃣ Feature Scaling

Used:

```python
StandardScaler
```

to normalize all features before clustering.

---

## 5️⃣ Dimensionality Reduction

Used:

```python
PCA (Principal Component Analysis)
```

Reduced high-dimensional data into 3 principal components for visualization and clustering efficiency.

---

## 6️⃣ Clustering Algorithms

### 🔹 K-Means Clustering

Used:

* Elbow Method
* WCSS
* Silhouette Score

to determine the optimal number of clusters.

### 🔹 Agglomerative Clustering

Applied hierarchical clustering using:

```python
linkage = "ward"
```

Final clusters were generated and analyzed.

---

# 📊 Visualizations

The project includes:

* Pairplots
* Heatmaps
* 3D PCA Cluster Visualization
* Elbow Curve
* Silhouette Score Analysis
* Cluster Distribution Countplots
* Income vs Spending Scatterplots

---

# 🏆 Final Results

Successfully segmented customers into multiple clusters based on:

* Purchasing behavior
* Income patterns
* Spending trends
* Family composition

These clusters can be used for:

✅ Personalized marketing
✅ Product recommendations
✅ Customer retention
✅ Business intelligence
✅ Sales optimization

---

# 🛠️ Tech Stack

| Category     | Technologies                       |
| ------------ | ---------------------------------- |
| Language     | Python                             |
| Libraries    | Pandas, NumPy, Matplotlib, Seaborn |
| ML Libraries | Scikit-Learn, Kneed                |
| Algorithms   | K-Means, Agglomerative Clustering  |
| Notebook     | Jupyter Notebook                   |

---

# 📁 Project Structure

```bash
SmartCart-Clustering-System/
│
├── Untitled.ipynb
├── smartcart_customers.csv
├── SmartCart Clustering System.pdf
├── README.md
│
└── outputs/
    ├── heatmap.png
    ├── elbow_curve.png
    ├── pca_clusters.png
    └── cluster_analysis.png
```

---

# ▶️ Installation & Setup

## Clone Repository

```bash
git clone https://github.com/your-username/SmartCart-Clustering-System.git
```

## Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn kneed
```

## Run Notebook

```bash
jupyter notebook
```

Open:

```bash
Untitled.ipynb
```

---

# 📈 Future Improvements

Possible future enhancements:

* Deploy using Streamlit
* Real-time customer segmentation
* Interactive dashboard
* Recommendation system integration
* Deep learning-based clustering
* Automated report generation

---

# 💡 Key Learnings

Through this project, I learned:

* Real-world data preprocessing
* Feature engineering techniques
* Dimensionality reduction using PCA
* Unsupervised machine learning
* Customer analytics
* Data visualization techniques
* Cluster interpretation

---





# 🔥 Project Highlights

✅ End-to-End ML Pipeline
✅ Real Retail Customer Data
✅ Advanced Feature Engineering
✅ PCA + Clustering Combination
✅ Multiple Visualization Techniques
✅ Business-Oriented Insights

---


