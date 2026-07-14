# Dataset Overview

**Dataset Shape:** There are 200 entries (customers) and 5 columns (features).

## Columns and Data Types

* **CustomerID:** Unique identifier for each customer (`integer`).
* **Gender:** Categorical variable (`object`).
* **Age:** Customer's age (`integer`).
* **Annual Income (k$):** Customer's annual income in thousands of dollars (`integer`).
* **Spending Score (1-100):** A score assigned by the mall based on customer behavior (`integer`).

---

# Clustering Algorithms

```text
Clustering
│
├── Partition Based
│      └── K-Means
│
├── Hierarchical
│      └── Agglomerative
│
├── Density Based
│      └── DBSCAN
│
└── Model Based
       └── Gaussian Mixture Model
