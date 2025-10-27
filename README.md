# End-to-End-Customer-Behavior-Analysis-SQL-Python-Power-BI-

# 🛍️ Customer Shopping Behavior Analysis  

## 📘 Overview  
This project explores and analyzes customer shopping patterns using transactional data to uncover insights about spending habits, demographics, and product preferences.  
It’s a complete **end-to-end data analytics pipeline** — from data loading and cleaning in Python, to SQL-based business queries, to dashboard creation in Power BI and reporting in Gamma.  

---

## 📊 Dataset  
- **Total Records:** 3,900  
- **Columns:** 18  
- **Key Features:**  
  - Customer demographics: `Age`, `Gender`, `Location`, `Subscription Status`  
  - Purchase details: `Item Purchased`, `Category`, `Purchase Amount`, `Season`, `Size`, `Color`  
  - Behavioral metrics: `Discount Applied`, `Promo Code Used`, `Previous Purchases`, `Review Rating`, `Shipping Type`  
- **Missing Data:** 37 missing values in `Review Rating`  

---

## 🧰 Tools & Technologies  
| Category | Tools Used |
|-----------|------------|
| Data Loading & EDA | Python (Pandas, NumPy, Matplotlib, Seaborn) |
| Database & SQL | MySQL / PostgreSQL / SQL Server |
| Dashboard | Microsoft Power BI |
| Reporting | Microsoft Word / PDF |
| Presentation | Gamma App |

---

## ⚙️ Steps in the Project  

### 1. **Data Loading (Python)**  
- Imported the CSV dataset using **pandas**.  
- Verified structure with `df.info()` and summary stats with `df.describe()`.  

### 2. **Data Cleaning**  
- Checked for missing values and handled nulls in `Review Rating` using **median imputation per category**.  
- Standardized column names to **snake_case** for readability.  
- Dropped redundant columns (`promo_code_used`).  

### 3. **Feature Engineering**  
- Created `age_group` (e.g., Teen, Adult, Senior).  
- Derived `purchase_frequency_days` to measure customer activity levels.  

### 4. **Database Integration**  
- Connected Python to **MySQL** via SQLAlchemy.  
- Exported the cleaned DataFrame into a SQL table (`customer_behavior`).  

### 5. **SQL Analysis (Business Insights)**  
Executed structured SQL queries to answer key questions:  
1. Revenue by Gender  
2. High-Spending Discount Users  
3. Top 5 Products by Rating  
4. Shipping Type Comparison  
5. Subscriber vs Non-Subscriber Revenue  
6. Discount-Dependent Products  
7. Customer Segmentation (New, Returning, Loyal)  
8. Top 3 Products per Category  
9. Repeat Buyers & Subscription Likelihood  
10. Revenue by Age Group  

### 6. **Dashboard in Power BI**  
- Created interactive visuals showing:  
  - **Total Revenue by Category**  
  - **Customer Segment Breakdown**  
  - **Discount Usage Impact**  
  - **Age Group vs Purchase Amount**  
- Used DAX measures and slicers for interactivity.  

### 7. **Report & Presentation**  
- Generated an analytical summary in **PDF** format.  
- Built an executive presentation using **Gamma App** summarizing findings and recommendations.  

---

## 📈 Dashboard Highlights  
- KPIs: Total Revenue, Avg Purchase Value, Active Customers, and Discount Usage Rate.  
- Filters for gender, category, and subscription status.  
- Visual storytelling to help decision-makers act quickly.  

---

## ✅ Results & Insights  
- Female customers contributed slightly higher total revenue.  
- Discounted purchases made up a large share of high-value transactions.  
- Loyal customers and subscribers consistently spent more.  
- Express shipping correlated with higher purchase value.  
- Top-rated products often overlapped with top revenue generators.  

 ## Screenshots / Demos
 <img width="1343" height="732" alt="Snapshot of Customer Behavior Dashboard" src="https://github.com/user-attachments/assets/943398ff-09b4-4257-8554-a47001bd481c" />
