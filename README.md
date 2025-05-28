# InfoTact-project

# 🧠 Customer Segmentation using K-Means Clustering

## 📌 Objective
This project performs customer segmentation on sales records using clustering techniques. The goal is to group customers based on common purchase behavior to enable targeted marketing strategies.

---

## 📁 Dataset
- **Source:** [Provided CSV: "New 1000 Sales Records"]
- **Size:** 1000 rows × multiple features
- **Key Features:**
  - Item Type, Region, Sales Channel, Order Date, Ship Date
  - Units Sold, Unit Price, Total Revenue, Total Profit, etc.

---

## 🛠️ Tools & Libraries
- Python 🐍
- pandas, NumPy
- scikit-learn
- seaborn, matplotlib
- PCA (for dimensionality reduction)

---

## 📅 Project Timeline

### Week 1: Data Cleaning & EDA
- Parse dates, extract order-ship days
- Handle data types and missing values
- Plot distributions of key numerical columns
- Analyze correlations and category breakdowns

### Week 2: Clustering
- Scale numeric features
- Apply K-Means clustering
- Determine optimal k (Elbow Method, Silhouette Score)
- Visualize clusters using PCA

### Week 3: Cluster Profiling & Strategy
- Analyze each cluster’s common traits
- Recommend marketing strategies
- Summarize clusters in a table

### Week 4: Final Outputs
- Prepare final report with visuals
- Build short presentation deck
- Deliver: Report, visuals, slide deck

---

## 📊 Key Findings

| Cluster | Units Sold | Total Profit | Unit Margin | Strategy |
|--------:|------------|--------------|-------------|----------|
|   0     | High       | Very High    | High        | Loyalty & Upselling |
|   1     | Low        | Low          | Moderate    | Retargeting |
|   2     | Medium     | Medium       | High        | Cross-sell |
|   3     | Varies     | Low          | Low         | Explore or Drop |

*Clusters based on scaled values and interpreted by domain context.*

---

## 📈 Visual Outputs
- Distribution plots for numerical features
- Heatmap of correlations
- Elbow and Silhouette charts
- Cluster visualized in PCA-reduced 2D space
- Bar plots per cluster for profiling

---

## 🎯 Recommendations
- Segment customers based on spending and product interest
- Use targeted campaigns per segment (loyalty, cross-sell, re-engagement)
- Focus on high-margin customers for premium offers

---

## 🚀 How to Run

```bash
pip install pandas matplotlib seaborn scikit-learn
python customer_segmentation.py
