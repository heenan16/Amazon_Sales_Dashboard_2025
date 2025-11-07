# Amazon_Sales_Dashboard_2025
Power BI Dashboard analyzing Amazon Diwali Product Sales 2025 using real-time Kaggle dataset


# 📊 Amazon Diwali Product Sales 2025 Dashboard

### 🎯 Project Overview
This Power BI project analyzes Amazon India's 2025 Diwali product sales performance to uncover key insights in sales trends, customer sentiment, and payment behavior.

---

### 🧩 Dataset Information
- **Source:** Kaggle (Amazon India Sales 2025)
- **Records:** 15,000+
- **Columns:** Date, Product Category, Product Name, Unit Price, Quantity, Total Sales, Payment Method, Sentiment, Review Rating, Country

---

### 📈 Key Metrics (KPIs)
- **Total Sales**
- **Total Quantity Sold**
- **Average Rating**
- **Distinct Customers**
- **Positive Reviews %**
- **Sales by Category & Product**

---

### 🧮 DAX Measures Used
- Total Sales = SUM([Total_Sales])
- Total Quantity = SUM([Quantity])
- Avg Rating = AVERAGE([Review_Rating])
- Positive Reviews = COUNTROWS(FILTER(Data, [Sentiment] = "Positive"))

---

### 📊 Visuals Used
- Clustered Column Chart – Sales by Category  
- Bar Chart – Top-Selling Products  
- Donut Chart – Payment Method Distribution  
- Map – Sales by Country  
- Cards – Total Sales, Quantity, Reviews, Ratings  
- Slicers – Date, Sentiment, Payment Method

---

### 🎨 Design Theme
- Background: Dark Mode (#0D0D0D)
- Accent: Amazon Orange (#F68B1E)
- Highlight: Amazon Blue (#0073BB)

---

### 💡 Insights
- Beauty and Electronics dominated sales.
- Credit Card and COD were top payment methods.
- Positive customer sentiment was higher during Diwali season.
- Country-wise sales show strong performance in India and nearby regions.

---

### 🧠 Tools & Skills
- **Tools:** Power BI  
- **Techniques:** Data Cleaning, DAX, Visualization, KPI Tracking  
- **Domain:** E-commerce, Retail Analytics  

---

### 📸 Dashboard Preview
![Dashboard Screenshot](Dashboard_Screenshot.png)

---

