# Team-Project-1 
# Housing Market Dynamics: Price Trends, Interest Rates, and Supply vs. Demand
# Questions:
1.	How do changes in interest rates correlate with housing prices?
2.	How have home prices evolved over time?
3.	How do fluctuations in rent data relate to changes in sales count and median sale prices over time?

# Project Overview
This project analyzes various aspects of the U.S. housing market from 2015 to 2024, focusing on key metrics such as interest rates, rent prices, sales count, median sale price, and total transaction value. The analysis aims to reveal trends and correlations between these metrics, helping to understand how interest rates influence housing prices, sales volume, and rent prices over time.
The project leverages Python, using libraries such as Pandas for data manipulation and matplotlib for data visualization.
Housing Market Data Analysis
 
# Data Files
The project uses the following CSV data files, sourced from Zillow and FRED, located in the Resources folder:
1.	MORTGAGE30US.csv: Historical U.S. mortgage interest rates.
2.	Metro_zori_uc_sfrcondomfr_sm_month.csv: Rent data for U.S. housing markets.
3.	Metro_total_transaction_value_uc_sfr_month.csv: Total transaction value data for U.S. housing markets.
4.	Metro_sales_count_now_uc_sfrcondo_month.csv: Sales count data for U.S. housing markets.
5.	Metro_median_sale_price_uc_sfr_month.csv: Median sale price data for U.S. housing markets.
6.	Metro_market_temp_index_uc_sfrcondo_month.csv: Market temperature index for U.S. housing markets.
 
# Key Functions & Workflow

1. Data Import and Preparation
The code imports multiple datasets using pandas, focusing on U.S. data by filtering where RegionName == 'United States'. Each dataset is cleaned, unnecessary columns are dropped, and the data is transposed for further analysis.

2. Interest Rate Data Processing
The interest rate data (MORTGAGE30US.csv) is filtered to focus on the time period from 2015 to 2024, converted into monthly data using resample(), and cleaned for further analysis.

3. Data Merging
Various metrics (e.g., sales count, median sale price, transaction value, rent data) are merged by the Date column to facilitate correlation and trend analysis.

4. Data Visualization
The code generates multiple plots to visualize trends in the housing market over time. Each visualization is saved as a PNG image in the Graphs folder:
•	Rent Prices Over Time
•	Sales Count and Median Sale Price Over Time
•	Total Transaction Value and Sales Count
•	Interest Rates vs. Median Sale Price

5. Correlation Analysis
The code calculates the correlation between metrics such as interest rates, sales count, and median sale price, showing insights like:
•	Moderate positive correlation between interest rates and median sale price.
•	Inverse correlation between lagged sales count and interest rates.

6. Advanced Analysis
The project includes advanced analysis such as lagged correlations to explore how past interest rates impact current sales and transaction values.
 
# Output
The code generates the following output:
1.	Graphs: Visualizations are saved in the Graphs folder:
	Rent Prices Over Time
	Total Transaction Value Over Time
	Sales Count and Median Sale Price Over Time
	Interest Rate vs. Median Sale Price
	Sales Count and Transaction Value Over Time
2.	Correlation Analysis: Printed correlation values between various metrics to understand their relationships.
 
# Future Considerations
This project demonstrates how interest rates and housing market dynamics are interconnected. Future improvements might include:
•	Adding regional analysis to see how different areas respond to interest rate changes.
•	Incorporating external economic indicators (e.g., unemployment rate, inflation) to provide a more comprehensive analysis.
•	Carrying out predictive analysis and forecasting housing market trends.
 
# License
This project is open-source and available under the MIT License.
