# Retail Customer Behavior Analysis

An end-to-end data analytics project exploring retail customer purchasing behavior, spending patterns, customer segments, and shopping trends using Python, PostgreSQL, and Power BI.

## Project Overview

The objective of this project is to analyze retail customer data and transform raw information into meaningful business insights that can support data-driven decision-making.

The project covers data preparation, exploratory data analysis, SQL-based business analysis, and interactive dashboard development.

## Technologies Used

- **Python:** Data cleaning, preprocessing, and exploratory data analysis
- **Pandas & NumPy:** Data manipulation and analysis
- **Matplotlib & Seaborn:** Data visualization
- **PostgreSQL:** Database management and SQL analysis
- **Power BI:** Interactive dashboards and visual reporting
- **Jupyter Notebook:** Python development environment
- **Git & GitHub:** Version control and project hosting

## Project Workflow

1. **Data Preparation and Cleaning – Python**
   - Imported and explored the retail customer dataset.
   - Handled missing values.
   - Renamed and transformed columns.
   - Created additional analytical features.
   - Prepared the cleaned dataset for database analysis.

2. **Exploratory Data Analysis – Python**
   - Examined customer demographics and purchasing patterns.
   - Explored spending behavior and product preferences.
   - Identified trends and relationships in the dataset.

3. **Business Analysis – PostgreSQL**
   - Loaded the cleaned dataset into PostgreSQL.
   - Developed SQL queries to answer business questions.
   - Analyzed customer segments, purchase behavior, payment methods, and seasonal trends.

4. **Data Visualization – Power BI**
   - Connected Power BI to the PostgreSQL database.
   - Developed a two-page interactive report.
   - Created KPI cards, charts, and slicers to explore customer behavior and purchasing insights.

## Dashboard Highlights

The Power BI report presents:

- Total purchase amount and average purchase amount.
- Customer count and average customer age.
- Purchase distribution across product categories.
- Purchase amount by gender and age group.
- Payment method preferences.
- Customer subscription status.
- Seasonal purchasing patterns.
- Interactive filters for category, gender, and season.

## Repository Structure

```text
Retail-Customer-Behavior-Analysis/
│
├── Customer_Shopping_Behavior_Analysis.ipynb
├── customer_behavior_sql_queries.sql
├── customer_shopping_behavior.csv
├── Retail_Customer_Behavior_Analysis.pbix
├── Business Problem Document.pdf
├── Customer Shopping Behavior Analysis.pdf
├── Customer-Shopping-Behavior-Analysis.pptx
├── README.md
└── LICENSE
```

## How to Run the Project

1. Clone this repository:

```bash
git clone https://github.com/TejaashriUK/Retail-Customer-Behavior-Analysis.git
```

2. Install the required Python libraries:

```bash
pip install pandas numpy matplotlib seaborn sqlalchemy psycopg2-binary jupyter
```

3. Open `Customer_Shopping_Behavior_Analysis.ipynb` in Jupyter Notebook or JupyterLab.

4. Execute the notebook to explore, clean, and prepare the dataset.

5. Create a PostgreSQL database and configure the database connection in the notebook.

6. Load the cleaned dataset into PostgreSQL and execute the queries in `customer_behavior_sql_queries.sql`.

7. Open `Retail_Customer_Behavior_Analysis.pbix` using Power BI Desktop. Configure the PostgreSQL connection if required.

## Project Learning Outcomes

- Practical experience with Python-based data cleaning and EDA.
- Understanding of SQL queries for business analysis.
- Experience connecting Python with PostgreSQL.
- Development of interactive reports using Power BI.
- Translating customer data into meaningful business insights.

## Acknowledgement

This project was developed as a learning and portfolio exercise, adapting concepts and the project structure from the retail customer behavior analysis tutorial by **Amlan Mohanty**.

Original learning resource: [Amlan Mohanty's YouTube Tutorial](https://www.youtube.com/watch?v=5PrZvPeUw60)

## Author

**Tejaashri K**

B.Tech – Artificial Intelligence and Data Science

GitHub: [TejaashriUK](https://github.com/TejaashriUK)

---

If you find this project useful, feel free to explore the repository and share your feedback!