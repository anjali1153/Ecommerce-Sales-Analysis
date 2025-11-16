# 🛒 E-Commerce Sales Analysis (Amazon Dataset)
### *End-to-End Data Analysis using Python, Pandas, Seaborn & Matplotlib*

![Banner](images/banner.png) <!-- optional -->

---

## 📌 Project Overview  
This project analyzes **E-Commerce product data (Amazon India)** to understand:

- Pricing patterns  
- Discounts  
- Customer ratings  
- Product category performance  
- Review text patterns  
- Correlations between different product attributes  

The aim is to demonstrate strong **data cleaning**, **exploratory data analysis (EDA)**, and **visual insight-generation** skills—core responsibilities of a Data Analyst.

---

## 🎯 Objectives  
- Clean and preprocess raw e-commerce product data  
- Convert prices, ratings, and discount values into usable numerical formats  
- Identify trends across product categories  
- Visualize patterns using Seaborn & Matplotlib  
- Generate business insights from data  
- Build a portfolio-ready analysis for recruiters  

---

## 📁 Dataset Description  
Each row represents an Amazon product listing. Key features:

| Column | Description |
|--------|-------------|
| `product_id` | Unique product identifier |
| `product_name` | Product title |
| `category` | Product category |
| `discounted_price` | Discounted price (₹) |
| `actual_price` | Original price (₹) |
| `discount_percentage` | Given discount (string) |
| `rating` | Customer rating (text) |
| `rating_count` | Number of customer ratings |
| `about_product` | Product description |
| `review_title` | Review title |
| `review_content` | Customer review text |

---

## 🧹 Data Cleaning & Preprocessing  
Steps performed:

✔ Removed `₹` and `,` and converted price columns to float  
✔ Extracted numeric values from rating text  
✔ Converted `rating_count` to integer  
✔ Calculated `discount_percent_calc` using formula  
✔ Removed null or invalid rows for analysis  
✔ Generated helper aggregated tables  
✔ Cleaned review text for wordcloud visualization  

---

## 📊 Exploratory Data Analysis (EDA)

### **1. Category Distribution**
Shows which categories have the most product listings.  
📎 *File:* `top_categories_count.png`

### **2. Price Distribution**
Histogram + KDE plot to understand typical pricing.  
📎 *File:* `price_distribution.png`

### **3. Boxplot of Price by Category**
Identifies expensive vs affordable categories.  
📎 *File:* `price_boxplot_by_category.png`

### **4. Rating vs Price (Regression)**
Tests if higher price leads to better ratings.  
📎 *File:* `rating_vs_price_regplot.png`

### **5. Average Rating by Category**
Shows customer satisfaction per category.  
📎 *File:* `avg_rating_by_category.png`

### **6. Average Discount by Category**
Which categories offer the highest discount %  
📎 *File:* `avg_discount_by_category.png`

### **7. Correlation Heatmap**
Evaluates numeric relationships (price, rating, discount).  
📎 *File:* `correlation_heatmap.png`

### **8. Wordcloud of Reviews**
Highlights common themes in reviews.  
📎 *File:* `reviews_wordcloud.png`

### **9. Jointplot, Swarmplot, Violinplot, Catplot, ECDF**  
Additional detailed plots for deeper insights.  

---

## 📝 Key Insights (Replace with your real results)
*(Add your real numbers after running code)*

- **Top category by listing count:** *Mobile Accessories (1,235 products)*  
- **Highest average customer rating:** *Headphones (avg rating 4.3)*  
- **Category with highest discount:** *Cables & Chargers (~38%)*  
- **Weak correlation between price and rating**, meaning expensive products don’t guarantee better ratings   
- **Price distribution is right-skewed**, meaning many cheap products and few high-end items  

---

## Tech Stack

- **Python**  
- **Pandas, NumPy**  
- **Seaborn, Matplotlib**  
- **Jupyter Notebook**  

---

## Folder Structure
