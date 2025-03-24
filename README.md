**Online Retail Exploratory Data Analysis with Python**

### **Case Study**
This project analyzes transactional data from an online retail store between 2010 and 2011. The goal is to uncover sales trends, customer behavior, and popular products, providing actionable insights for strategic business decisions.

### **Dataset**
The dataset used in this project is the **"Online Retail"** dataset from Kaggle ([source](https://www.kaggle.com/datasets/vijayuv/onlineretail)). It contains transactional data of an online retail store and includes the following key columns:
- **InvoiceNo**: Invoice number
- **StockCode**: Unique product code
- **Description**: Product description
- **Quantity**: Quantity of products in the transaction
- **InvoiceDate**: Date and time of the transaction
- **UnitPrice**: Unit price of the product
- **CustomerID**: Unique customer identifier
- **Country**: Country where the transaction occurred

Prior to analysis, the dataset was cleaned by removing duplicates, handling missing values, and transforming date formats.

### **Data Cleaning and Preparation**
- **Removed duplicates:** 5,268 duplicate records were dropped.
- **Handled missing values:** 1,454 missing product descriptions and 135,037 missing customer IDs were removed.
- **Addressed negative quantities:** Transactions with invoice numbers starting with 'C' were identified as canceled orders and treated accordingly.

### **Key Findings**
#### **1. Daily Sales Analysis**
- Sales volumes peaked during the first and last months of 2011, likely due to holiday shopping trends.
- High sales spikes suggest seasonal demand patterns.

#### **2. Daily Return Analysis**
- Return volumes were highest in the first and last months of the year.
- The return rate remained relatively stable throughout the year.

#### **3. Sales Distribution by Country**
- **United Kingdom (86.9%)** accounted for the majority of sales.
- Other top markets included Germany, France, Ireland, and Spain.

#### **4. Most Popular Products**
| Product | Sales Frequency |
|---|---|
| WHITE HANGING HEART T-LIGHT HOLDER | 2,023 |
| REGENCY CAKESTAND 3 TIER | 1,714 |
| JUMBO BAG RED RETROSPOT | 1,615 |
| ASSORTED COLOUR BIRD ORNAMENT | 1,395 |
| PARTY BUNTING | 1,390 |

- Popular products mainly include home decor and kitchenware items.

#### **5. Most Returned Products**
- "REGENCY CAKESTAND 3 TIER" had the highest number of returns.
- High-value products experienced the most cancellations.

#### **6. Top Customers by Revenue**
- **Customer 14646** (Netherlands) generated the highest revenue of **$280,206.02**.
- **Top 5 customers**: 14646 (Netherlands), 18102 (UK), 17450 (UK), 16446 (UK), 14911 (Ireland).

### **Insights and Recommendations**
✔ **Stock levels should be adjusted based on seasonal demand patterns.**
✔ **Return reasons should be analyzed to improve product quality and customer satisfaction.**
✔ **Loyalty programs should be introduced to retain high-value customers.**
✔ **Marketing efforts should focus on the best-selling products for higher profitability.**

### **Technologies Used**
- **Python** (Pandas, NumPy, Seaborn, Matplotlib)
- **SQL** (Data querying and analysis)
- **Jupyter Notebook** (Data analysis and visualization)

This analysis provides valuable insights to help the online retail store make data-driven business decisions and optimize its sales strategies.

