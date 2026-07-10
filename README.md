# retail-analytics
An end-to-end data analytics project analyzing customer shopping behavior using Python (Pandas), MySQL and Power BI.

## Project Workflow

### 1. Data Loading

* Imported the dataset into Python.
* Examined data structure and basic statistics.

### 2. Data Cleaning, Exploratory Data Analysis (EDA)

* Removed missing values.
* Checked and removed duplicate records.
* Corrected data types.
* Prepared the dataset for analysis.
  
### 3. SQL Analysis

* Imported cleaned data into MySQL.
* Wrote SQL queries to answer business questions and run queries to extract insights on customer segments, loyalty.
  
### 4. Power BI Dashboard

Developed an interactive dashboard to visualize:

* Sales Overview
* Customer Demographics
* Product Category Performance
* Payment Method Analysis
* Shopping Trends
* Key Performance Indicators (KPIs)

---

## Project Structure

```text
retail-analytics/
│
├── Dataset/
│   ├── customer_shopping_behavior.csv
│
├── Python/
│   ├── customer_Analysis.ipynb
│   
├── SQL/
│   ├── customer_trends_script.sql
│
├── PowerBI/
│   ├── customer_trends_dashboard.pbix
│
├── Report/
│   ├── project-report.pdf
│
└── README.md
```

## How to Run

1. Clone this repository.

```bash
git clone https://github.com/byvishwanath/retail-analytics.git
```

2. Open the Jupyter Notebook.

3. Install the required Python libraries.

```bash
pip install pandas 
```

4. Run the notebook

5. Import the cleaned dataset into MySQL and execute the SQL queries.

6. Open the Power BI dashboard (`.pbix`) to explore the interactive visualizations.

---

## Future Improvements

* Build predictive machine learning models.
* Automate the data pipeline.
* Connect Power BI to a live database.


---

## Author

**Vishwanath Bavandla**


---

## License

This project is intended for educational and portfolio purposes.



