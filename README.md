# Financial Forecasting Model & PnL Statement
Excel Financial Forecasting Model and PnL Statement using historical NYSE data


# Explanation
Dynamic dashboards for a Profit and Loss Statement and Forecasting Model using statistical analysis on historical NYSE data. 
- Excel functions such as INDEX(), MATCH(), OFFSET()
- Summary Statistics
- Dynamic (auto-updating) spreadsheets
- Four sheets total: 
  - Projectdata_NYSE
  - Summary Statistics
  - PnL Statement
  - Forecasting Model


# Files
## NYSE_Kannianen.xlsx
- Excel file containing all sheets

### Projectdata_NYSE
- raw data received for project
  ##### Columns
    - Index
    - Symbol
    - Year_num
    - Year
    - Total_Revenue
    - CoGS
    - Sales_General_and_Admin
    - Research_and_Development
    - Other_Operating_Items
    - GICS_Sector
    - GICS_Industry
    - symbol_list

### Summary Statistics
Statistical analysis answering the question: "Which IT sub-industry spent the most on average CoGS?"
- Pivot Tabel utitlized to find Average CoGS across the IT industry.  
- Secondary table finds Difference from Mean CoGS by sub-industry.
- Two Visualizations presenting:
  - +/- Average CoGS of IT Sector
  - 5 Number Summary w/Outliers
- Statistical analysis including:
  - Min
  - Q1 (25%)
  - Q2 (50%)
  - Q3 (75%)
  - Max
  - Mean
  - Median
  - Range (Max - Min)
  - IQR (Inter-Quartile Range; Q3 - Q1)
  - Std Dev (Standard Deviation)


### PnL Statement
Dynamic 4 Year Profit and Loss Statement changing upon selecting a new symbol from the Yellow drop down menu.
- Total Revenue
  - Costs of Goods Sold
- Gross Profit
  - Sales, General, and Admin
  - Research and Development
  - Other operating expenses
- Total operating expenses
- Operating income/EBIT

### Forecasting Model
Dynamic Financial Forecasting Model changning upon selecting a new symbol from the Yellow drop down menu.

##### Income Statement
- same as PnL statement with Years 1-4
- plus Forecast years (2018, 2019, 2020)

##### Operating Statistics
- Revenue Growth (%)
- Gross Margin
- Operating Margin

##### Scenarios:
- Weak case (-0.01%)
- Base case (0.0%)
- Strong case (+0.01%)

# Tools
- Spreadsheet reader (Excel, etc)


# References
Udacity
- Data Analyst Coursework

<a href="https://www.geeksforgeeks.org/how-to-merge-multiple-csv-files-into-a-single-pandas-dataframe/">Geeks for Geeks</a>
- Used for combining multiple .csv files with pd.concat() and map()

# Contact Information
**Name:** Jared R. Kannianen

**Organization:** Masterschool - Data Analyst

**Email:** jarkanni@campus.masterschool.com
