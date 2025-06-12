# SQlite-Database



# 📊  Basic Sales Summary using SQLite and Python

🎯 Objective

This task demonstrates how to:

Create and use a small SQLite database in Python

Run SQL queries from Python using sqlite3

Summarize basic sales data (total quantity and revenue by product)

Display results using print() and a simple bar chart with matplotlib



---

🧰 Tools & Libraries

Python 3.x

sqlite3 (built-in)

pandas

matplotlib

Jupyter Notebook


📁 Files Included

File	Description

sales_data.db	SQLite database with a sample sales table
sales_summary.ipynb	Jupyter Notebook performing the full analysis
sales_chart.png	Output chart showing revenue per product 



---

🧪 Dataset Description

The database contains a single table called sales with the following columns:

Column	Type	Description

id	INTEGER	Primary key
product	TEXT	Product name (e.g., Apples)
quantity	INTEGER	Number of units sold
price	REAL	Price per unit



---

🛠 Steps Performed

1. Create Database and Table

Used sqlite3 to create a sales_data.db file and a sales table



2. Insert Sample Data

Populated the table with dummy data for Apples, Bananas, and Oranges



3. Run SQL Query

Queried total quantity and revenue per product using SQL



4. Load into Pandas

Loaded query result into a pandas DataFrame for easy analysis



5. Print Results

Displayed the summary using print(df)



6. Plot with Matplotlib

Created a bar chart showing revenue per product

Added labels, grid lines, and saved the chart as sales_chart.png




📊 Sample Output

Printed Table:

product  total_qty  revenue
0  Apples         17      8.5
1 Bananas         11      3.3
2 Oranges         12      4.8

Chart:

Bar chart comparing revenue across products, labeled and grid-enabled.


---

🚀 How to Run

# Install required packages if not already installed
pip install pandas matplotlib

Then run the notebook or script:

# In Jupyter Notebook
jupyter notebook sales_summary.ipynb

# Or as a .py file
python sales_summary.py


---

✅ Learning Outcomes

Working with SQLite databases in Python

Executing SQL queries inside Python

Visualizing data using matplotlib

Understanding basic data analysis workflows




