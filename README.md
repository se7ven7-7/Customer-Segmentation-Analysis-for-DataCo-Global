# 🧩 Customer Segmentation Analysis for DataCo Global

### Team Members: Yufei Shang, Shrinidhi Bhide, Ohm Srikiatkhachorn, Wenlin Zhao  
Date: March 2025  

---

## 📘 Project Overview 

This project develops a **multi-faceted customer segmentation framework** for DataCo Global.  
We integrate both **transactional data** (purchase amount, discount usage, shipping time) and **behavioral data** (clickstream and browsing patterns) to improve **targeted marketing**, **conversion optimization**, and **customer retention** strategies.  


---

## 🧠 Key Objectives 
1. **Behavioral Segmentation – Clickstream Aggregation**  
   Identify high-interest, low-conversion products through browsing data analysis.  
2. **Temporal & Sequential Pattern Analysis**  
   Explore peak browsing vs purchase hours to optimize campaign timing.  
3. **Hybrid Clustering for Customer and Product Segmentation**  
   Apply K-Means and Hierarchical Clustering to uncover meaningful customer and product groups.

---

## 🧰 Methods & Techniques Used 

- **Data Sources:**
  
  https://data.mendeley.com/datasets/8gx2fvg2k6/5   
  - DataCo Smart Supply Chain for Big Data Analysis (Mendeley Dataset)  
  - Tokenized Access Logs (Clickstream Data)

- **Techniques:**  
  - Exploratory Data Analysis (EDA): Correlation & Skewness Analysis, Outlier Handling  
  - **PCA (Principal Component Analysis)** for Dimensionality Reduction  
  - **K-Means Clustering & Hierarchical Clustering** for Customer Segmentation  
  - **UMAP** for Non-linear Structure Discovery and Visualization  
  - **Topic Modeling** for Product Interest Classification  

- **Tools:** Python (NumPy, Pandas, Scikit-Learn, Matplotlib), Google Colab  

---

## 💡 Key Findings 

- **High Correlation & Feature Reduction:** Removed redundant variables (e.g., Sales vs Profit).  
- **Skewness Correction:** Used log and exponential transformations to normalize data.  
- **Effective Dimensionality Reduction:** ~30 principal components preserve 95 % variance.  
- **Optimal Clustering:** UMAP + K-Means (k = 2) achieved Silhouette Score ≈ 0.69.  
- **Business Implications:** Helps identify loyal customers, optimize discount strategies, and target promotion timing.

---

## ⚠️ Important Notes 

- The file **`Customer-Segmentation-Analysis-for-DataCo-Global.zip`** contains the **Google Colab Notebook**.  
  Please **download and extract** it locally to view the source code.

- You can **also view the notebook online** via the link:  
  👉 [**Open Colab Notebook (Online View)**](https://drive.google.com/file/d/1SwuREC0R9m6CH6TltL2ZSxva40SgG0vx/view?usp=sharing)
