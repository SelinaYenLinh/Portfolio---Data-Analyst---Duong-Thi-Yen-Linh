# Data Analyst Portfolio — Duong Thi Yen Linh

**Email**: selina.duong97@gmail.com 

**Phone**: +84 354 241 419 

**Location**: Binh Duong, Vietnam 

**LinkedIn**: [LinkedIn Dương Thị Yến Linh](www.linkedin.com/in/dương-thị-yến-linh-140a67216)

**GitHub**: [Github Dương Thị Yến Linh](https://github.com/SelinaYenLinh)

Entry‑level Data Analyst with a forecasting background. Hands‑on with SQL, Power BI (DAX/M), Python (Pandas), and data storytelling. Built sales & operations dashboards and contributed to ~+10% forecast‑accuracy via seasonality and standardized inputs.

### Highlights / Achievements  
- Contributed to +10% forecast‑accuracy by standardizing inputs and integrating seasonality into analysis & dashboards.

- Power BI storytelling dashboards (cards → trends → drill‑through) improving business visibility and reducing manual reporting.

- ETL automation with VBA/Power Query, cutting report prep time (fill actual: ↓X%).

**Tech Stack**: SQL · Power BI (DAX/M) · Python (Pandas/Matplotlib) · Excel/Power Query · Star Schema · Basic ML/Forecasting

### Projects
#### **Power BI Sales & Operations — Storytelling Dashboard**  
**Goal**: Give leadership and planners a clear narrative of performance (Sales/Inventory/Delivery) within 30 seconds.  
**Dataset**: Orders/Items, Customers, Products, Dates (sample or anonymized real structure).  
**Model**: Star Schema (Fact Orders/Items; Dim Customers/Products/Dates).  
**Key KPIs**: Gross Sales, Margin, Stock Coverage, Stockout Rate, OTIF/Lead Time.  
**Visual Design**: Cards → Trend → Drill‑through; role‑based pages (Director / Sales / Ops).  
**Performance**: load < 3s (fill); refresh daily/weekly (fill); adoption +N MAU (fill).  
Stack: Power BI, DAX/M, SQL, Power Query.  

#### **Python — EDA (Roller Coaster Design Evolution)**

**Goal:** Clean the dataset and uncover actionable insights about coaster designs over time.  
**Tools & Libraries:** `pandas`, `matplotlib`, `seaborn`, `ydata_profiling`  

**Key Skills Demonstrated**
- Data cleaning & preprocessing (Pandas)
- Exploratory visualizations (Matplotlib/Seaborn)
- Aggregation & basic statistics
- Correlation analysis & decade-based trend analysis
- Automated reporting with `ydata-profiling`

**Highlights / Findings**
- Coaster **speed** and **height** have **increased significantly** across decades.
- **Steel vs. wooden** coasters show **distinct design trends** (speed/height/inversions).
- Modern coasters are not only **faster** but also **more intense** (higher **G-force**).

**Repo Tips (optional)**
- Put the CSV in `data/`, notebook in `notebooks/01_eda_coasters.ipynb`, screenshots in `reports/screenshots/`.
- Export an HTML profiling file as `reports/EDA_Report.html` for quick review.
#### **Smart Loan Recovery System - Machine Learning**
**Features**:   
- Data visualization using Plotly  
- Data preprocessing pipeline  
- Clustering borrowers via KMeans  
- Classification using RandomForest  
- Evaluation metrics & model export  
- Modular structure for maintainability  

**Model Training & Evaluation**:
- Clustering: KMeans (4 clusters)  
- Segment borrowers into risk profiles (from 0 to 4).  
- Classification: Random Forest  
- Label segments as recoverable or not.  
- Metrics:  
    - Accuracy: 96%  
    - Precision: 91%  
    - Recall: 97%  
    - F1 Score: 94%  

**🧾 Dependencies**:
- Key libraries:  
    - pandas, scikit-learn  
    - plotly, matplotlib, seaborn  
    - yaml    