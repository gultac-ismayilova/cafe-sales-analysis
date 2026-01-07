
## Cafe Sales Analysis (Excel + Python)

### Overview

This project analyzes cafe sales transactions to identify customer purchasing behavior, sales trends, and revenue drivers.
Data cleaning and preprocessing were performed in **Excel using Power Query**, while **exploratory data analysis (EDA)** and visualizations were conducted using **Python**.


### Dataset

The dataset contains cafe transaction records including:

* Transaction ID
* Item
* Quantity
* Price per Unit
* Total Spent
* Payment Method
* Location (In-store / Takeaway / Unknown)
* Transaction Date


### Tools Used

* Microsoft Excel (Power Query for data cleaning)
* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook


### Data Cleaning Process

Data cleaning was performed in **Excel using Power Query** with the following steps:

* Removed rows with missing or invalid values in **critical fields** (e.g., Transaction ID, Item, Price per Unit, Transaction Date)
* Replaced missing values in the **Quantity** column with `1` to reflect minimum valid sales where transactions were confirmed
* Standardized categorical values by replacing `ERROR` and `UNKNOWN` entries in **Location** with a unified `Unknown` category
* Converted all numeric and date fields to appropriate data types
* Recalculated **Total Spent** as `Quantity × Price per Unit` to ensure consistency and accuracy
* Exported the cleaned dataset as a CSV file for further analysis in Python


### Exploratory Data Analysis (EDA)

* Total and average sales analysis
* Sales distribution by product
* Monthly sales trend analysis
* Comparison of sales by location and payment method
* Item-level revenue and quantity analysis



### Key Insights

* In-store and takeaway channels generate similar sales volumes, but in-store purchases tend to have a higher average order value.
* Cash is the most frequently used payment method and is associated with higher total spending.
* Products such as **Salad** and **Juice**, **Smoothie** generate higher overall revenue, indicating strong demand for healthier options.
* Monthly sales exhibit noticeable fluctuations, suggesting seasonal purchasing behavior.
* A noticeable decline is observed in February sales. This drop is likely influenced by the shorter number of days in February and post-holiday seasonality rather than a sustained decrease in demand.



### Visualizations

* Monthly sales trend (line chart)
* Sales by item (bar chart)
* Sales by location (bar chart)
* Item and location sales comparison (stacked bar chart)



### Conclusion

This analysis provides actionable insights into customer preferences, product performance, and sales channels.
The findings can support improved inventory planning, targeted promotions, and payment strategy optimization.

