# Customer Shopping Behavior Analysis

End-to-end data analytics project covering Python, SQL, Power BI, and a final presentation, built to uncover customer purchase patterns and support smarter business decisions.

---

## Overview

This project analyzes customer shopping behavior to understand **who buys, what they buy, and how much they spend**. It follows a complete analytics workflow: loading and cleaning the data in Python, querying it with SQL, visualizing it in Power BI, and presenting the findings in a report and slide deck.

**Business questions answered:**
- Which customer segments generate the most revenue?
- What products and categories are most popular?
- How do discounts, subscriptions, and purchase frequency affect spending?
- Which age groups and locations contribute the most sales?

---

## Dataset

| Detail | Info |
|---|---|
| **File** | `customer_shopping_behavior.csv` |
| **Source** | [Add source, e.g. Kaggle link] |
| **Rows / Columns** | [Add number of rows] / [Add number of columns] |

**Key columns:** Customer ID, Age, Gender, Item Purchased, Category, Purchase Amount (USD), Location, Size, Color, Season, Review Rating, Subscription Status, Discount Applied, Previous Purchases, Frequency of Purchases.

> Update this table to match your actual dataset.

---

## Tools & Technologies

| Purpose | Tool |
|---|---|
| Data loading, EDA, cleaning | Python (Pandas, NumPy, Matplotlib, Seaborn), Jupyter Notebook |
| Database and queries | SQL ([PostgreSQL / MySQL / SQL Server: keep the one you used]) |
| Dashboard | Power BI |
| Report | [Word / PDF] |
| Presentation | Gamma (AI-powered slides) |
| Version control | Git and GitHub |

---

## Project Steps

### 1. Data Loading and EDA (Python)
- Loaded the dataset into a Pandas DataFrame
- Checked structure, data types, summary statistics, and distributions
- Explored patterns using charts and grouped summaries

### 2. Data Cleaning (Python)
- Handled missing values
- Removed duplicates and fixed inconsistent data types
- Standardized column names
- Created new columns where useful (for example, age groups)

### 3. SQL Analysis
- Loaded the cleaned data into [PostgreSQL / MySQL / SQL Server]
- Wrote queries to answer business questions, such as:
  - Total revenue by gender and category
  - Top-selling products
  - Average spend by subscription status
  - Impact of discounts on purchase amount
  - Customer segmentation by purchase frequency

### 4. Power BI Dashboard
- Connected Power BI to the cleaned data
- Built interactive visuals with filters and KPI cards
- Designed the dashboard for quick business insights

### 5. Report
- Summarized methodology, findings, and recommendations in a written report

### 6. Presentation (Gamma)
- Created a slide deck with Gamma to present key insights to a non-technical audience

---

## Dashboard

![Power BI Dashboard](images/dashboard.png)

> Add a screenshot of your dashboard to an `images/` folder and update the file name above.

**Dashboard highlights:**
- KPI cards: total revenue, number of customers, average purchase amount, average rating
- Sales by category, location, and season
- Customer breakdown by age group, gender, and subscription status
- Interactive filters for deeper exploration

---

## Results

Add your real findings here. Example format:

- **Top category:** [Category] generated the highest revenue at [X]%
- **Spending pattern:** [Group] customers spend [more/less] on average than [Group]
- **Discounts:** Customers who used discounts spent [higher/lower] on average
- **Subscriptions:** Subscribers made [more/fewer] repeat purchases
- **Recommendation:** [One clear, actionable business suggestion]

---

## How to Run

### Prerequisites
- Python 3.8 or higher
- Jupyter Notebook
- [PostgreSQL / MySQL / SQL Server]
- Power BI Desktop (Windows)

### Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/lahuchavan/customer_shopping_data_analysis.git
   cd customer_shopping_data_analysis
   ```

2. **Install Python libraries**
   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```

3. **Run the notebook**
   ```bash
   jupyter notebook customer_shopping_behavior.ipynb
   ```

4. **Run the SQL queries**
   - Create a database and load the cleaned data
   - Open `customer_Shopping_sql_queries.sql` in your SQL client and run the queries

5. **Open the dashboard**
   - Open the `.pbix` file in Power BI Desktop and refresh the data source if needed

---

## Repository Structure

```
customer_shopping_data_analysis/
│
├── customer_shopping_behavior.csv        # Dataset
├── customer_shopping_behavior.ipynb      # Python EDA and cleaning
├── customer_Shopping_sql_queries.sql     # SQL analysis queries
├── dashboard.pbix                        # Power BI dashboard
├── report.pdf                            # Project report
├── presentation.pdf                      # Gamma presentation
├── images/                               # Dashboard screenshots
├── LICENSE
└── README.md
```

> Adjust file names to match what is actually in your repo.

---

## Acknowledgements

This project was created while following a tutorial by **[Creator Name]** on YouTube: [Video link]. The code has been modified and extended with my own analysis.

---

## License

This project is licensed under the [MIT License](LICENSE).

---

## Author

**Lahu Chavan**
- GitHub: [@lahuchavan](https://github.com/lahuchavan)
- LinkedIn: [Add your LinkedIn link]
- Email: [Add your email]
