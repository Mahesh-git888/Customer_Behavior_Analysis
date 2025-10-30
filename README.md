#  Customer Shopping Behavior Analysis

##  1. Overview
This project explores customer shopping patterns using transactional data from 3,900 purchases across multiple product categories.  
It combines **Python**, **PostgreSQL**, and **Power BI** to uncover insights into spending trends, customer segmentation, and subscription impact — supporting strategic business decisions.

---

##  2. Objectives
- Identify high-revenue customer groups and product categories  
- Compare spending habits by gender, age group, and subscription status  
- Evaluate how discounts, shipping types, and review ratings influence sales  
- Visualize findings through an interactive Power BI dashboard  

---

## 3. Project Files

| File Name | Description |
|------------|-------------|
| **Customer Shopping Behavior Analysis.pdf** | Final project report summarizing objectives, methods, findings, and recommendations |
| **Customer-Behavior-Analysis.pptx** | Presentation slides (Gamma/PowerPoint) summarizing insights and visuals |
| **QUERIES.sql** | SQL queries used for business transaction analysis in PostgreSQL |
| **README.md** | Documentation file describing the project workflow and dataset |
| **customer_behavior_dashboard.pbix** | Power BI dashboard with interactive visualizations |
| **customer_shopping_behavior.csv** | Original dataset containing 3,900 purchase records across 18 features |
| **data_analysis.ipynb** | Python notebook for data loading, cleaning, EDA, and PostgreSQL integration |

---

##  4. Tools and Technologies
- **Python** – pandas, numpy, matplotlib, seaborn  
- **PostgreSQL** – SQL-based data querying and analysis  
- **Power BI Desktop** – Dashboard development and visualization  
- **Gamma / PowerPoint** – Presentation and reporting  
- **Excel / CSV** – Data storage and inspection  

---

##  5. Project Workflow

### 1. Data Preparation (Python)
- Imported and cleaned the dataset  
- Handled missing values (imputed median review ratings per category)  
- Standardized column names to `snake_case`  
- Engineered new features like `age_group` and `purchase_frequency_days`  
- Loaded cleaned data into PostgreSQL  

### 2. Business Analysis (SQL)
Executed structured queries to answer business questions:
- Revenue by gender and age group  
- Comparison of Standard vs. Express shipping  
- Top 5 products by average review rating  
- High-spending customers using discounts  
- Subscription vs. non-subscription revenue analysis  
- Segmentation into **New**, **Returning**, and **Loyal** customers  

### 3. Dashboard Development (Power BI)
- Built an interactive dashboard highlighting demographics, sales trends, and top-performing products  
- Designed KPI visuals for management review  

### 4. Reporting
- Summarized findings in **PDF report** and **presentation slides** for stakeholders  

---

##  6. Key Insights
- Subscribers spend significantly more than non-subscribers  
- Express shipping correlates with higher purchase amounts  
- Certain products rely heavily on discounts to drive sales  
- Higher review ratings align with repeat customer behavior  

---

##  7. Business Recommendations
- **Boost Subscriptions:** Offer exclusive benefits to increase membership  
- **Loyalty Programs:** Reward repeat customers to strengthen retention  
- **Review Discount Strategy:** Balance discount offers with margin control  
- **Product Positioning:** Highlight top-rated and high-demand products  
- **Targeted Marketing:** Focus campaigns on high-value age groups and express-shipping users  

---

##  8. How to Run the Project

1. Open `data_analysis.ipynb` in Jupyter Notebook or VS Code  
   - Run all cells to clean and prepare the dataset  
   - Load the cleaned data into PostgreSQL  

2. Execute SQL queries from `QUERIES.sql` in your database  

3. Open `customer_behavior_dashboard.pbix` in Power BI Desktop  
   - Connect to your data source if needed  
   - Explore the dashboard interactively  

4. Review final documentation:  
   - `Customer Shopping Behavior Analysis.pdf` (Detailed Report)  
   - `Customer-Behavior-Analysis.pptx` (Presentation Slides)  

---



---
