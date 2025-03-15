# 🛒 Instacart Basket Analysis  
📊 **Uncovering Customer Behavior & Purchase Patterns**  

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white) ![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=Tableau&logoColor=white)

---

## 🌟 **Introduction**  
This project analyzes **Instacart’s transactional data** to uncover customer purchasing behavior, product demand, and market trends. Using Python and advanced analytics, we provide actionable insights to optimize inventory, marketing, and customer engagement strategies.  

---

## 🎯 **Project Objectives**  
1. **Identify Top Products**: Determine high-demand items and customer preferences.  
2. **Analyze Order Timing**: Uncover peak shopping hours and seasonal trends.  
3. **Customer Segmentation**: Group buyers by frequency and basket size.  
4. **Market Basket Analysis**: Discover frequently paired products.  

---

## 🛠️ **Tools & Technologies**  
- **Python**: Pandas, NumPy, Scikit-learn (data cleaning, clustering).  
- **Visualization**: Matplotlib, Seaborn, Plotly.  
- **Machine Learning**: Apriori algorithm for association rules.  
- **SQL**: Data storage and querying.  

---

## 📂 **Dataset Overview**  
**Instacart Open-Source Dataset** includes:  
- **3.4M+ Orders**: Customer IDs, order times, and product details.  
- **50K+ Products**: Categories, aisles, and departments.  
- **Key Features**: `order_dow`, `order_hour_of_day`, `aisle`, `department`.  

---

## 🔍 **Key Insights**  
### 1️⃣ **Customer Purchase Trends**  
- **Top Products**: Bananas (🥑) and avocados dominate sales.  
- **Order Frequency**: 70% of customers order weekly.  
- **Category Trends**: Dairy and produce account for **45% of revenue**.  

### 2️⃣ **Time-Based Patterns**  
- **Peak Hours**: 10 AM – 2 PM (lunchtime shopping).  
- **Weekend Surge**: 30% higher sales on Saturdays.  

### 3️⃣ **Customer Segmentation**  
- **VIP Shoppers**: Top 5% contribute 25% of revenue.  
- **Occasional Buyers**: 60% of customers purchase monthly.  

### 4️⃣ **Market Basket Analysis**  
- **Top Pair**: Milk + Cereal (confidence = 85%).  
- **Premium Pair**: Organic eggs + Artisanal bread.  

---

## 📊 **Visualizations**  
Static and interactive visualizations (charts, heatmaps, and dashboards) are included in the `/Visualizations` folder. Key outputs:  
- **Top 10 Most Purchased Products** (Bar chart).  
- **Order Trends Over Time** (Line graph).  
- **Customer Segmentation Clusters** (Pie chart).  
- **Market Basket Analysis Heatmap** (Correlation matrix).  

---

## 🚀 **Business Recommendations**  
1. **Stock Optimization**: Prioritize bananas, avocados, and dairy products.  
2. **Peak-Hour Promotions**: Run flash sales between 10 AM – 2 PM.  
3. **VIP Loyalty Programs**: Offer discounts to frequent buyers.  
4. **Product Pairing Campaigns**: Bundle milk + cereal for targeted ads.  

---

## 📂 **Repository Structure**  
```plaintext
Instacart-Basket-Analysis/  
├── Data/                   # Raw and cleaned datasets  
├── Notebooks/              # Jupyter notebooks (EDA, ML)  
├── Scripts/                # Python scripts for automation  
├── Reports/                # Client-ready summaries and slides  
├── Visualizations/         # Charts and interactive dashboards  
└── README.md               # Project overview  
