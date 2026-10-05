# Customer Behavior Data Analyst Portfolio Project

This project demonstrates an end-to-end customer analytics workflow that mirrors how a business analyst works in a real-world environment. It covers the complete lifecycle of data analytics, from raw data preparation and SQL analysis to dashboarding and business storytelling.

## Project Overview

The goal of this project is to transform raw customer shopping data into actionable insights that support business decisions related to:

- customer segmentation
- purchase behavior trends
- loyalty program effectiveness
- product and category performance
- revenue drivers and customer value

This portfolio project is designed to showcase practical analytics skills using Python, SQL, and Power BI.

## Business Objective

The dataset is analyzed to answer key business questions such as:

- Who are the most valuable customer segments?
- Which product categories generate the highest revenue?
- How do age, gender, and membership status influence shopping behavior?
- What factors drive repeat purchases and customer loyalty?
- Which insights can help improve marketing and retention strategies?

## Tech Stack

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SQL (MySQL / PostgreSQL / SQL Server)
- Power BI

## Project Workflow

1. Data import and exploration in Python
2. Data cleaning and preprocessing
3. Exploratory Data Analysis (EDA)
4. SQL-based business analysis
5. Power BI dashboard development
6. Insight generation and recommendation writing

## Repository Contents

- `Customer_Shopping_Behavior_Analysis.ipynb` — Python notebook for data loading, cleaning, EDA, and SQL export logic
- `customer_shopping_behavior.csv` — raw customer shopping dataset
- `customer_behavior_sql_queries.sql` — SQL queries for customer behavior analysis
- `customer_behavior_dashboard.pbix` — Power BI dashboard file
- `Business Problem  Document.pdf` — business problem statement and context
- `Customer Shopping Behavior Analysis.pdf` — project analysis report
- `Customer-Shopping-Behavior-Analysis.pptx` — presentation deck
- `README.md` — project overview and usage instructions

## Prerequisites

Before running the project, make sure you have the following installed:

- Python 3.9 or later
- Jupyter Notebook or VS Code with Jupyter support
- A SQL database such as MySQL, PostgreSQL, or SQL Server
- Power BI Desktop
- Access to the dataset file in the repository

## Python Setup

Clone the repository:

```bash
git clone https://github.com/Abhinav0965/customer-trends-data-analysis-SQL-Python-PowerBI.git
cd customer-trends-data-analysis-SQL-Python-PowerBI
```

Create a virtual environment:

```bash
python -m venv .venv
```

Activate the environment:

- Windows:

```bash
.venv\Scripts\activate
```

- macOS/Linux:

```bash
source .venv/bin/activate
```

Install the required Python packages:

```bash
pip install pandas numpy matplotlib seaborn sqlalchemy pymysql psycopg2-binary pyodbc openpyxl
```

Open and run `Customer_Shopping_Behavior_Analysis.ipynb` to:

- load the dataset
- inspect schema and missing values
- clean and transform the data
- perform exploratory analysis
- connect to a SQL database
- export the final dataset into SQL

For the PostgreSQL connection cell, configure `DB_USER`, `DB_PASSWORD`, and
`DB_NAME` in your environment before running it. `DB_HOST` and `DB_PORT` are
optional and default to `localhost` and `5432`. Keep credentials out of the
notebook and repository.

## SQL Analysis

1. Create a database in your preferred SQL engine.
2. Run the Python notebook to load the cleaned data into SQL.
3. Open `customer_behavior_sql_queries.sql`.
4. Execute the queries to answer business questions related to:
   - customer segments
   - loyalty and membership trends
   - purchase frequency
   - revenue contribution
   - category and item performance

## Power BI Dashboard

1. Open `customer_behavior_dashboard.pbix` in Power BI Desktop.
2. Connect the dashboard to your SQL database.
3. Refresh the data model.
4. Build visualizations for key metrics and trends.
5. Add slicers and filters to create an interactive dashboard.

## Expected Outputs

This project aims to produce:

- cleaned and structured customer dataset
- SQL analysis queries and insights
- interactive Power BI dashboard
- business recommendations
- presentation-ready summary report

## Project Insights

The analysis is expected to highlight patterns such as:

- high-value customer segments
- product categories with strongest demand
- differences in spend by age and gender
- impact of membership status on purchase behavior
- the relationship between customer engagement and revenue

## Report and Presentation

Use the project files to prepare final documentation and stakeholder communication:

- `Business Problem  Document.pdf` for project context
- `Customer Shopping Behavior Analysis.pdf` for a formal analysis summary
- `Customer-Shopping-Behavior-Analysis.pptx` for a presentation deck

## License

MIT License — feel free to fork, star, and use this project as part of your portfolio.

## Acknowledgement

Thanks for checking out this project. I hope it helps demonstrate practical data analytics thinking, SQL skills, Python-based data preparation, and dashboard storytelling in a real business context.
