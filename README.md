# Customer Behavior Data Analytics Project

## 📌 Overview
This project analyzes customer purchasing behavior using a structured, end-to-end data analytics workflow — from raw data ingestion to business insights and stakeholder-ready reporting. The goal is to uncover patterns in customer spending, product performance, and shipping preferences to support data-driven decision-making.

The workflow covers the full analytics lifecycle: data loading and cleaning in Python, exploratory data analysis (EDA), SQL-based querying for business questions, interactive dashboarding in Power BI, and a final report and presentation summarizing key findings.

---

## 📂 Dataset
- **Source:** [Add dataset source, e.g., Kaggle / company-provided / synthetic dataset]
- **Format:** CSV
- **Size:** [Add number of rows/columns]
- **Key fields:** `customer_id`, `age`, `gender`, `item_purchased`, `purchase_amount`, `discount_applied`, `review_rating`, `shipping_type`, `payment_method`, `frequency_of_purchases`

---

## 🛠️ Tools & Technologies
| Category | Tools Used |
|---|---|
| Programming | Python (Pandas, NumPy, Matplotlib/Seaborn) |
| Database | PostgreSQL / MySQL / SQL Server |
| Visualization | Power BI |
| Reporting | Word / PDF report |
| Presentation | Gamma (AI-generated PPT) |
| Environment | Jupyter Notebook, pgAdmin 4 |

---

## 🔄 Project Workflow / Steps

1. **Data Loading**
   - Imported the raw dataset into Python using Pandas
   - Performed initial inspection (shape, data types, missing values)

2. **Data Cleaning**
   - Handled missing/null values
   - Standardized column names and data types
   - Removed duplicates and corrected inconsistent categorical values

3. **Exploratory Data Analysis (EDA)**
   - Analyzed distributions of purchase amount, age, and review ratings
   - Explored relationships between gender, discount usage, and spending
   - Visualized trends using Matplotlib/Seaborn

4. **SQL Analysis**
   - Loaded the cleaned dataset into PostgreSQL/MySQL/SQL Server
   - Wrote SQL queries to answer key business questions, including:
     - Revenue comparison across gender segments
     - Customers using discounts who still spent above average
     - Top 5 products by average review rating
     - Purchase amount comparison across shipping types

5. **Power BI Dashboard**
   - Connected Power BI to the SQL database
   - Built interactive visuals (cards, charts, filters) to summarize KPIs
   - Enabled drill-down and filtering for deeper exploration

6. **Reporting**
   - Compiled findings into a structured written report with insights and recommendations

7. **Presentation**
   - Created a summary presentation using Gamma for stakeholder communication

---

## 📊 Dashboard
The Power BI dashboard highlights:
- Total customers and average purchase amount
- Revenue breakdown by gender and category
- Average review ratings by product
- Purchase trends by shipping type and discount usage

*(Add a screenshot or link to the published Power BI dashboard here)*

---

## 📈 Results & Key Insights
- [Add 3–5 concise insights, e.g.]
- Male and female customers show comparable revenue contribution, with a slight lead in [category].
- Customers using discounts still spent above the average purchase amount, suggesting discounts do not significantly cannibalize order value.
- Top 5 products by review rating indicate strong customer satisfaction in [category].
- Express shipping customers show [higher/lower] average purchase amounts compared to standard shipping.

---

## ▶️ How to Run This Project

1. **Clone the repository**
```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
```

2. **Set up the Python environment**
```bash
   pip install -r requirements.txt
```

3. **Run the data cleaning & EDA notebook**
```bash
   jupyter notebook eda_and_cleaning.ipynb
```

4. **Load data into your SQL database**
   - Import the cleaned CSV into PostgreSQL/MySQL/SQL Server
   - Run the queries in `queries.sql` to reproduce the analysis

5. **Open the Power BI dashboard**
   - Open `dashboard.pbix` in Power BI Desktop
   - Refresh the data connection to point to your local database

6. **View the report and presentation**
   - Report: `report.pdf`
   - Presentation: `presentation.pdf` (created with Gamma)

---

## 📁 Project Structure
