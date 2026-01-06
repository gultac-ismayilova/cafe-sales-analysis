## Cafe Sales Analysis (Excel + Python)

### Overview
This project analyzes cafe sales transactions to identify customer purchasing behavior, sales trends, and revenue drivers.
Data cleaning was performed in Excel using Power Query, while exploratory data analysis (EDA) and visualizations were conducted using Python.

### Dataset
The dataset contains cafe transaction records including:
- Transaction ID
- Item
- Quantity
- Price per Unit
- Total Spent
- Payment Method
- Location (In-store / Takeaway)
- Transaction Date

### Tools Used
- Microsoft Excel (Power Query for data cleaning)
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

### Data Cleaning Process
- Removed rows with missing, invalid, or inconsistent values (ERROR, UNKNOWN, null)
- Standardized data types (numeric and datetime)
- Verified calculated fields such as Total Spent
- Exported clean dataset for Python analysis

### Exploratory Data Analysis (EDA)
- Total and average sales analysis
- Sales distribution by product
- Monthly sales trend analysis
- Comparison of sales by location and payment method
- Item-level revenue and quantity analysis

### Key Insights
- In-store and takeaway channels generate similar sales volumes, but in-store purchases tend to have a higher average order value.
- Digital Wallet is the most used payment method and is associated with higher total spending.
- Products such as Salad and Juice generate higher overall revenue, indicating strong demand for healthier options.
- Monthly sales show noticeable fluctuations, suggesting seasonal purchasing behavior.

### Visualizations
- Monthly sales trend (line chart)
- Sales by item (bar chart)
- Sales by location (bar chart)
- Item and location sales comparison (stacked bar chart)

### Conclusion
The analysis provides actionable insights into customer preferences, product performance, and sales channels.
These findings can support better inventory planning, targeted promotions, and payment strategy optimization.
