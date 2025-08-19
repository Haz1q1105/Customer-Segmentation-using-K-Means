# Customer-Segmentation-using-K-Means
This project applies Unsupervised Learning (K-Means Clustering) to the Mall Customers Dataset to group customers into meaningful segments.
## Dataset  
- **Mall_Customers.xlsx**  
- Contains information on customer demographics and spending behavior:  
  - CustomerID  
  - Gender  
  - Age  
  - Annual Income (k$)  
  - Spending Score (1-100)  
  - Marital Status  

---

## Steps  

### 1. Data Preprocessing  
- Handled missing values  
- Encoded categorical variables (Gender, Marital Status)  
- Standardized numerical features  

### 2. Exploratory Data Analysis (EDA)  
- Distribution of age, income, and spending score  
- Spending patterns across gender and marital status  

### 3. Clustering (K-Means)  
- Used **Elbow Method** to find optimal K (best at **K=4**)  
- Built K-Means model and assigned customers to clusters  

### 4. Dimensionality Reduction & Visualization  
- Applied **PCA** to reduce data to 2D  
- Visualized clusters on scatter plots  

### 5. Cluster Profiling & Marketing Strategy  
- Interpreted cluster characteristics  
- Proposed targeted marketing strategies  

---

## Results  

- **Cluster 0:** Older, mid-income, moderate spenders → loyalty/value deals  
- **Cluster 1:** Young, high-income, high spenders → premium offers, VIP programs  
- **Cluster 2:** Very young, low-income, but active spenders → discounts, trendy items  
- **Cluster 3:** Wealthy, but low spenders → reactivation campaigns, exclusivity offers  

---
