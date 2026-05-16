# SCT_ML_2
# 🛍️ Customer Segmentation using K-Means Clustering

This project implements the **K-Means Clustering Algorithm** to group retail store customers based on their purchase behavior.

Customer groups are created using:
- Age
- Annual Income
- Spending Score

The goal is to identify different customer segments for better business understanding and marketing strategies.

---

# 📂 Dataset

Dataset Used:
- `Mall_Customers.csv`

Dataset Shape:
```text
200 rows × 4 columns
```

Features:
- `id`
- `age`
- `income`
- `score`

---

# 🚀 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

# 📊 Features Used for Clustering

| Feature | Description |
|---|---|
| age | Customer age |
| income | Annual income |
| score | Spending score assigned by mall |

---

# 🧠 Machine Learning Algorithm

Algorithm Used:
- **K-Means Clustering**

K-Means groups customers into clusters based on similarities in customer behavior.

---

# ⚙️ Project Workflow

1. Load dataset
2. Explore customer data
3. Select important features
4. Apply K-Means clustering
5. Create customer segments
6. Visualize clusters
7. Save clustered dataset and graph

---

# 📄 Dataset Summary

```text
               id         age      income       score
count  200.000000  200.000000  200.000000  200.000000
mean   100.500000   38.850000   60.560000   50.200000
std     57.879185   13.969007   26.264721   25.823522
min      1.000000   18.000000   15.000000    1.000000
25%     50.750000   28.750000   41.500000   34.750000
50%    100.500000   36.000000   61.500000   50.000000
75%    150.250000   49.000000   78.000000   73.000000
max    200.000000   70.000000  137.000000   99.000000
```

---

# 📈 Cluster Profiles

```text
Cluster Profiles:
           age  income  score  size
cluster                           
0        46.2    26.8   18.4    20
1        25.2    41.1   62.2    54
2        32.9    86.1   81.5    40
3        39.9    86.1   19.4    39
4        55.6    54.4   48.9    47
```

---

# 📌 Cluster Interpretation

| Cluster | Description |
|---|---|
| 0 | Low income, low spending customers |
| 1 | Young customers with medium spending |
| 2 | High income, high spending customers |
| 3 | High income, low spending customers |
| 4 | Older customers with average spending |

---

# 🖼️ Output Files Generated

```text
mall_kmeans_complete.png
customers_clustered.csv
```

---

# 💻 Complete Output

```text
               id         age      income       score
count  200.000000  200.000000  200.000000  200.000000
mean   100.500000   38.850000   60.560000   50.200000
std     57.879185   13.969007   26.264721   25.823522
min      1.000000   18.000000   15.000000    1.000000
25%     50.750000   28.750000   41.500000   34.750000
50%    100.500000   36.000000   61.500000   50.000000
75%    150.250000   49.000000   78.000000   73.000000
max    200.000000   70.000000  137.000000   99.000000

Cluster Profiles:
           age  income  score  size
cluster                           
0        46.2    26.8   18.4    20
1        25.2    41.1   62.2    54
2        32.9    86.1   81.5    40
3        39.9    86.1   19.4    39
4        55.6    54.4   48.9    47

```
