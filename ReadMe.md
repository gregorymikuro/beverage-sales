# Beverage Sales Analysis

## Project Overview
This project focuses on analyzing wholesale beverage sales across different regions, customer types, and product categories. The dataset contains information about sales transactions, including pricing, discounts, and order details. The analysis aims to uncover regional preferences, seasonal trends, pricing strategies, and customer segmentation insights.

## File Structure
```
Beverage-Sales/
│── data/
│   │── archive.zip  # Compressed dataset file
│   │── synthetic_beverage_sales_data.csv  # Main dataset containing sales data
│── .gitignore  # File to exclude certain files and folders from Git tracking
│── index.ipynb  # Jupyter Notebook for data exploration and analysis
```

### **1. `data/` Folder**
- **`archive.zip`**: A compressed file containing the dataset (backup copy).
- **`synthetic_beverage_sales_data.csv`**: The main dataset, which includes detailed sales records.

### **2. `.gitignore`**
- Prevents unnecessary files from being tracked by Git.
- Currently ignores:
  - The `data/` folder (to avoid tracking large files)
  - `.zip` and `.csv` files to keep the repository clean.

### **3. `index.ipynb`**
- A Jupyter Notebook for exploring, cleaning, and analyzing the beverage sales data.
- Includes visualizations and insights on product demand, pricing trends, and regional preferences.

## Dataset Overview
The dataset provides a synthetic representation of beverage sales and includes the following key columns:
- **Order_ID**: Unique identifier for each order.
- **Customer_ID**: Unique identifier for each customer.
- **Customer_Type**: Defines whether the customer is B2B (business-to-business) or B2C (business-to-consumer).
- **Product**: Name of the beverage product purchased.
- **Category**: Beverage category (e.g., Water, Soft Drinks, Alcoholic Beverages, Juices).
- **Unit_Price**: Price per unit of the product.
- **Quantity**: Number of units purchased.
- **Discount**: Discount applied to B2B customers.
- **Total_Price**: Total sales value for the product after applying discounts.
- **Region**: Customer's region (e.g., Hamburg, Bayern, Saarland).
- **Order_Date**: Date of the transaction.

