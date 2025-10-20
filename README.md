# 🛍️ RFM Analysis on Online Retail Company

Imagine you own a big retail company and want to create a **membership program** for customers 🎁.  
You want to give **rewards or incentives** based on customer's shopping behavior.  

In this case, transforming raw data into an **informative summary using RFM**, which contains customer shopping habits, can help determine giving **bonus to each personal member** 💡.  

---

## 📊 RFM Components

1. **🕒 Recency**: tracking customer last transaction from current date  
2. **🔁 Frequency**: count total orders for overall transaction  
3. **💰 Monetary**: count total spending of customer by multiplying **price × quantity**  

---

After getting the three important columns (RFM), classify their similar behavior using **Machine Learning clustering (K-Means)** 🤖  

### Steps:
1. **🔧 Standardize all features** into uniform format (remove very large and very small values)  
2. **📉 Determine K** using the elbow method  
3. **🚀 Apply the model** into modified RFM data  
4. **📦 Grouping** based on each K number and count each average  

---

## 🎯 Outcome

- Number of **Champion, Loyal, At-Risk, Lost** customers based on K-values and average numbers  
- Marketers can leverage these values on marketing strategies:  
  - Give **discounts or free new product launches** to Champion or Loyal customers 🏆  
  - Send **notification reminders, coupons, or bundling packages** to Lost or At-Risk customers to drive purchase intention 🔔  

---

## 🧾 Dataset

**Online retail dataset**:  
`[C:\Users\Lenovo\Downloads\online+retail](https://www.kaggle.com/datasets/mashlyn/online-retail-ii-uci)`  

This dataset is used to calculate RFM metrics and segment customers for effective marketing strategies.
