# Prism-Insurance---Claims-and-Policy-Performance-Overview
# 📊 Power BI Prism - Insurance Claims & Policy Performance Dashboard  

## 🚀 Project Overview  
Power BI Prism is a comprehensive dashboard designed to analyze **insurance claims, policy performance, and customer feedback**.  
The project incorporates **Sentiment Analysis**, **Drill-Through Filters**, and **Scheduled Refresh** to deliver valuable insights.  

---

## 📌 Features  

### 1️⃣ **Dashboard Overview (Main Report)**
🔹 Displays key insurance claim metrics like **Premium Amount, Coverage Amount, and Total Claims**  
🔹 Gender-wise segmentation of claim numbers  
🔹 Breakdown of claim status (**Rejected, Settled, Pending**)  
🔹 Distribution of claim amounts by **Policy Type & Age Group**  
🔹 **Active vs. Inactive Policies** visualized using a donut chart  
🔹 Interactive filters for **Policy Number, Claim Number, and Customer ID**  

🖼 **Dashboard Screenshot:**  
![Dashboard View](https://github.com/Shivansh7678/Prism-Insurance---Claims-and-Policy-Performance-Overview/blob/main/Dashboard%20View/Dashboard%20view%201.png?raw=true)  

---

### 2️⃣ **Table View (Data Exploration)**
🔹 Provides a tabular view of all **insurance claim records**  
🔹 Contains fields such as **Customer ID, Claim Number, Age, Gender, Coverage Amount, Premium Amount, Policy Start/End Date, Claim Status, and Claim Date**  
🔹 Enables easy validation and exploration of **insurance records**  

🖼 **Table View Screenshot:**  
![Table View](https://github.com/Shivansh7678/Prism-Insurance---Claims-and-Policy-Performance-Overview/blob/main/Dashboard%20View/Dashboard%20view%202.png?raw=true)  

---

### 3️⃣ **Customer Feedback & Sentiment Analysis**
🔹 **Word Cloud Visualization** to highlight frequent terms in customer feedback  
🔹 **Sentiment Score Calculation** based on feedback (Positive, Negative, Neutral)  
🔹 Categorized feedback insights: **Excellent, Good, Needs Improvement**  
🔹 Helps identify **customer satisfaction trends** and areas for service improvement  

🖼 **Sentiment Analysis Screenshot:**  
![Sentiment Analysis](https://github.com/Shivansh7678/Prism-Insurance---Claims-and-Policy-Performance-Overview/blob/main/Dashboard%20View/Dashboard%20view%203.png?raw=true)  

---

## 🎯 **Technical Implementation**  

### ✅  Sentiment Analysis (Text Processing)**
- Used **Power BI Text Analytics** to classify customer feedback  
- Implemented **Score Sentiment Measure** to categorize feedback into:  
  - Positive (Above 0.5)  
  - Neutral (0.3 - 0.5)  
  - Negative (Below 0.3)  
