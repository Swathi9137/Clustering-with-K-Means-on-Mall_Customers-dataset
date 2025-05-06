# 🧠 Task 8: K-Means Clustering - Mall Customer Segmentation

This project is part of an AI & ML Internship, focusing on **unsupervised learning** using **K-Means Clustering**. We segment customers based on their annual income and spending score.

---

## 📁 Dataset

- **File**: `Mall_Customers.csv`
- **Source**: [Kaggle - Customer Segmentation](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)

---

## 🚀 Tools & Libraries

- Python
- Scikit-learn
- Pandas
- Matplotlib
- Seaborn

---

## 🔍 Objective

- Apply K-Means clustering to segment mall customers.
- Visualize customer groups and understand their spending behavior.
- Use the Elbow Method to find the optimal number of clusters.
- Evaluate clustering performance using Silhouette Score.

---

## 📊 Steps Performed

1. **Loaded and cleaned the dataset**
2. **Selected relevant features** for clustering: `Annual Income` and `Spending Score`
3. **Standardized** the data using `StandardScaler`
4. **Applied the Elbow Method** to determine optimal number of clusters (K)
5. **Fitted K-Means** with chosen K value
6. **Visualized clusters** using scatter plot
7. **Evaluated model** using Silhouette Score

---

## 📈 Visual Output

- Elbow Method plot
- Customer segmentation plot (colored by cluster)

---

## ✅ Results

- **Optimal K**: 5
- **Silhouette Score**: ~0.55 (indicates fairly good separation of clusters)

---

## 📂 Files in this Repo

- `Mall_Customers.csv` - Dataset
- `task8_kmeans_colab.ipynb` - Notebook with full implementation
- `README.md` - This file

---


