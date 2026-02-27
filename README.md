# Sales Performance and Revenue Analysis

##  Project Overview
This project demonstrates an **end-to-end analytics workflow** using Python (VS Code) for data cleaning, preprocessing, and exploratory analysis, and Power BI for interactive dashboard development.  
The goal is to analyze **Superstore sales data** to uncover revenue drivers, category performance, segment insights, and regional trends.

---

##  Workflow

### 1. Data Preparation (Python in VS Code)
- Imported raw dataset (`superstore.csv.csv`).
- Handled missing values and duplicates.
- Converted date columns (`Order_Date`, `Ship_Date`) to datetime format.
- Engineered new features:
  - `Year`, `Month`, `Quarter`
  - `Processing_Days` (shipping duration)
- Exported cleaned dataset as `superstore_clean.csv`.

### 2. Exploratory Data Analysis (Python)
- Calculated KPIs:
  - **Total Sales**
  - **Average Order Value**
  - **Average Processing Days**
- Analyzed sales by **Category** and **Segment**.
- Built pivot tables for **Category vs Region**.
- Visualized:
  - Sales distribution (histogram)
  - Category counts (bar chart)
  - Monthly sales trend (line chart)
  - Correlation heatmap (Sales vs Processing Days)

### 3. Dashboard Development (Power BI)
- Imported `superstore_clean.csv`.
- Built interactive visuals:
  - KPI Cards (Total Sales, AOV, Avg Processing Days, Max Sale Value)
  - Line Chart (Monthly/Yearly Sales Trend)
  - Bar Chart (Sales by Category)
  - Stacked Bar Chart (Segment vs Category)
  - Map (Sales by State/Region)
  - Matrix Table (Category vs Region)
- Saved dashboard as `sales_dashboard.pbix`.

---

##  Key Insights
- **Technology** category drives the highest revenue.
- **Consumer** segment dominates across categories.
- **West region** consistently outperforms other regions.
- **Processing Days** vary by shipping mode but show no strong correlation with sales.
- Seasonal peaks in sales are visible across years.

---

##  Deliverables
- **Notebook:** `notebooks/analysis.ipynb`  
- **Python Script:** `notebooks/analysis.py`  
- **Cleaned Dataset:** `data/superstore_clean.csv`  
- **Dashboard:** `dashboards/sales_dashboard.pbix`  
- **Documentation:** `README.md`  

---

##  How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/KummethaLatha/sales-performance-analysis.git
