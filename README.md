# customer-segmentation-unsupervised-learnin
# 🛍️ Customer Segmentation Using Unsupervised Learning

## 📌 Project Overview
This project focuses on **customer segmentation** using the **Mall Customers dataset**.  
We apply **unsupervised machine learning (K-Means clustering)** to group customers based on their **Annual Income** and **Spending Score**.  
Dimensionality reduction techniques such as **PCA** and **t-SNE** are used to visualize the clusters effectively.  

The final outcome is a set of **customer segments** with **tailored marketing strategies**.

---

## 🎯 Objectives
- Perform **Exploratory Data Analysis (EDA)** on customer data.
- Apply **K-Means clustering** to segment customers.
- Use **PCA and t-SNE** for cluster visualization.
- Propose **marketing strategies** for each customer group.

---

## 📊 Dataset
**Mall Customers Dataset**  
- **CustomerID** – Unique ID assigned to the customer  
- **Gender** – Male/Female  
- **Age** – Customer’s age  
- **Annual Income (k$)** – Annual income in thousand dollars  
- **Spending Score (1-100)** – Score assigned based on customer behavior and spending nature  

---

## 🧑‍💻 Skills Gained
- Unsupervised Learning (K-Means clustering)  
- Dimensionality Reduction (PCA, t-SNE)  
- Data Visualization (Matplotlib, Seaborn)  
- Business Strategy Development  

---

## 📈 Approach
1. **Data Exploration**
   - Summary statistics and visualizations of Age, Income, and Spending Score.
2. **Clustering with K-Means**
   - Used **Elbow Method** to determine optimal clusters (k=5).
3. **Visualization**
   - Scatterplots with clusters.
   - PCA for 2D cluster visualization.
   - t-SNE for advanced visualization.
4. **Cluster Insights**
   - Summarized customer groups.
   - Proposed **targeted marketing strategies**.

---

## 🖼️ Visualizations
- Distribution plots (Age, Income, Spending Score)
- Elbow Method for optimal clusters
- Cluster scatter plots
- PCA visualization
- t-SNE visualization

---

## 🏷️ Marketing Strategies (Example)
- **Cluster 0**: High income, high spenders → Luxury promotions, VIP loyalty programs.  
- **Cluster 1**: Low income, low spenders → Discounts and budget-friendly offers.  
- **Cluster 2**: Young, medium income, high spenders → Trendy products, social media campaigns.  
- **Cluster 3**: High income, low spenders → Premium services, upselling strategies.  
- **Cluster 4**: Average income and spending → General promotions, seasonal campaigns.  

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/customer-segmentation-unsupervised-learning.git
   cd customer-segmentation-unsupervised-learning
