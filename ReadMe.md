
---

# **Beverage Sales Data Analysis**  

## **Table of Contents**  
- [Introduction](#introduction)  
- [Business Understanding](#business-understanding)  
- [Problem Statement](#problem-statement)  
- [Project Objectives](#project-objectives)  
- [Data Overview](#data-overview)  
- [Analysis & Methodology](#analysis--methodology)  
- [Key Findings](#key-findings)  
- [Recommendations](#recommendations)  
- [Usage & How to Run](#usage--how-to-run)  
- [Technologies Used](#technologies-used)  
- [Contributors](#contributors)  

---

## **Introduction**  
This project aims to analyze beverage sales data to extract meaningful insights that can help businesses optimize their pricing strategies, improve customer segmentation, and enhance overall sales performance. By leveraging data analytics, the project uncovers patterns in customer purchasing behavior, product performance, and sales trends over time.  

---

## **Business Understanding**  
The beverage industry is highly competitive, requiring businesses to continuously adapt to changing consumer preferences and market trends. Data-driven insights are essential for companies to make informed decisions regarding pricing, discounting, and inventory management. This project provides a structured analysis of beverage sales data to support strategic decision-making.  

---

## **Problem Statement**  
Despite the availability of extensive sales data, many businesses struggle to derive actionable insights that drive growth. Challenges include:  
- Understanding differences in purchasing behavior between *B2B* and *B2C* customers.  
- Identifying high-performing and underperforming beverage categories.  
- Evaluating the impact of pricing and discounts on revenue.  
- Recognizing seasonal and regional sales trends to optimize marketing strategies.  

This project aims to bridge this gap by applying data analytics to extract meaningful patterns and trends.  

---

## **Project Objectives**  
The main objectives of this project are:  
1. To analyze customer purchasing behavior across *B2B* and *B2C* segments.  
2. To evaluate the sales performance of different beverage categories.  
3. To assess the impact of pricing and discounts on total revenue.  
4. To identify seasonal and regional sales trends.  
5. To provide data-driven recommendations for improving sales strategies.  

---

## **Data Overview**  
The dataset consists of beverage sales transaction data that simulates real-world sales scenarios. It contains the following key variables:  

| **Column**       | **Description** |
|-----------------|----------------|
| **Order_ID**    | Unique identifier for each sales transaction. |
| **Customer_ID** | Unique identifier assigned to each customer. |
| **Customer_Type** | Categorization as either *B2B* (business-to-business) or *B2C* (business-to-consumer). |
| **Product**     | Name of the beverage product purchased. |
| **Category**    | Classification of the product into major beverage categories (e.g., *Soft Drinks, Juices, Water*). |
| **Unit_Price**  | Price per unit of the product at the time of sale. |
| **Quantity**    | Number of units purchased in a given transaction. |
| **Discount**    | Percentage discount applied to the order. |
| **Total_Price** | Total sales value after applying the discount. |
| **Region**      | Geographical location where the order was placed. |
| **Order_Date**  | Date when the transaction occurred. |

---

## **Analysis & Methodology**  
This project applies the following data analysis techniques:  

1. **Exploratory Data Analysis (EDA)** – Visualizing distributions, identifying outliers, and summarizing key statistics.  
2. **Correlation Analysis** – Examining relationships between variables such as *price, discount, and total revenue*.  
3. **Time-Series Analysis** – Analyzing revenue trends over time and detecting seasonality.  
4. **Customer Segmentation** – Using clustering techniques to group customers based on purchasing patterns.  
5. **Predictive Modeling** – Applying regression analysis to evaluate factors influencing total revenue.  

---

## **Key Findings**  
Based on the analysis, the following key insights were derived:  

- **B2B customers** tend to make larger purchases, contributing significantly to total revenue.  
- Certain beverages, such as *Hohes C Orange and Granini Apple*, are consistently high-selling products.  
- Discounts negatively impact revenue, suggesting that businesses should optimize discounting strategies.  
- Monthly revenue trends indicate seasonal variations in sales, which should be factored into inventory planning.  
- Certain regions, such as *Hamburg, Bayern, and Baden-Württemberg*, generate higher revenue than others.  

---

## **Recommendations**  
Based on the analysis, the following recommendations are suggested:  

1. **Customer Segmentation Strategies**  
   - Implement targeted marketing campaigns for *B2B and B2C customers*.  
   - Develop loyalty programs for *B2C customers* to encourage repeat purchases.  
   - Offer bulk purchase incentives for *B2B customers* to maximize high-value transactions.  

2. **Pricing and Discount Optimization**  
   - Reduce excessive discounts and apply targeted promotions based on purchase behavior.  
   - Implement dynamic pricing models to adjust product prices based on demand trends.  
   - Conduct A/B testing on pricing strategies to optimize revenue.  

3. **Product Performance Management**  
   - Focus marketing efforts on best-selling products while re-evaluating underperforming ones.  
   - Introduce new product variants based on consumer preferences.  
   - Optimize inventory levels based on category-level demand insights.  

4. **Regional and Seasonal Sales Strategies**  
   - Allocate marketing budgets based on high-revenue regions.  
   - Adjust inventory levels based on seasonal demand fluctuations.  
   - Create localized marketing campaigns tailored to regional preferences.  

5. **Data-Driven Decision Making**  
   - Develop predictive models to forecast sales trends and demand fluctuations.  
   - Implement real-time customer analytics to adjust marketing efforts dynamically.  
   - Use AI-powered recommendation systems to personalize product suggestions.  

---

## **Usage & How to Run**  
To run this project, follow these steps:  

### **1. Clone the Repository**  
```bash
git clone https://github.com/your-repo/beverage-sales-analysis.git
cd beverage-sales-analysis
```

### **2. Install Dependencies**  
```bash
pip install -r requirements.txt
```

### **3. Run the Analysis**   
```bash
jupyter notebook
```
and open `Beverage_Sales_Analysis.ipynb`.  

### **4. View Results**  
The results, including visualizations and key findings, will be saved in the `output/` directory.

---

## **Technologies Used**  
- **Python** (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Statsmodels)  
- **Jupyter Notebook** for interactive analysis  
- **Git & GitHub** for version control  

---

## **Contributors**  
- **Ivy Atieng**
- **Gregory Mikuro**  

---

## **License**  
This project is open-source and available under the **MIT License**.  

---
