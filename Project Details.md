# Housing Market Dynamics: Price

## Possible Analysis:

- **Time Series Analysis**: Examine changes in property prices and rental rates over time, correlating these with fluctuations in supply (e.g., new construction) and demand (e.g., population growth or migration patterns).

- **Supply vs. Demand Heatmaps**: Create geographic heatmaps showing areas where housing demand significantly exceeds supply, resulting in price increases. Conversely, identify regions where supply is greater than demand, leading to price stagnation or decreases.

- **Interest Rate vs. Price Correlation**: Analyze how interest rate changes impact housing affordability and demand, specifically looking at how lower rates fuel demand (and increase prices) versus how higher rates suppress demand.

- **Affordability Analysis**: Compare the cost of renting vs. buying, incorporating interest rates, housing supply, and local income levels. Identify regions where affordability challenges exist due to mismatches between demand and available housing supply.

- **Demographic and Regional Trends**: Explore how supply and demand pressures differ across regions and demographics, such as how urban areas may face higher demand for rentals due to limited supply, while suburban/rural areas experience shifts in home ownership due to different affordability dynamics.

- **Construction and Supply Tracking**: Analyze rates of new home construction and compare them to housing demand in different regions. Examine how lagging construction in high-demand areas exacerbates price growth, while areas with higher supply may see stabilized or declining prices.



Key Questions:: 
For a data analysis project on Housing Market Dynamics focused on price trends, interest rates,
and supply vs. demand, you should ask a variety of questions to guide your analysis. These 
questions should cover various aspects of the housing market, from data collection to 
interpretation of insights


1. How do changes in interest rates correlate with housing prices?
2. Supply & Demand Heatmap : Are there significant increases or decreases in the construction of new homes?
3. Do high-cost housing markets react differently to interest rate changes compared to lower-
cost regions?


Focus:
2014-2024 



:: Findings as of 9/18

Interest Rate and Median Sale Price Over Time (Graph 1)
Analysis: This graph shows the movement of interest rates (in blue) and median sale prices (in green) from 2015 to 2025. A clear upward trend is observed in the median sale prices, especially post-2020, despite fluctuations in the interest rate.
Interpretation: Higher interest rates are typically associated with lower housing demand, as borrowing becomes more expensive, which should depress housing prices. However, in this case, median sale prices are increasing even as interest rates rise. This could indicate other factors driving demand (e.g., supply shortages, inflationary pressures, etc.).
Expansion Ideas:
Add lagged effects of interest rates on sale prices. The housing market may take time to react to interest rate changes, so plotting a lagged version of the interest rate may reveal more about the relationship.
Investigate other economic variables (e.g., inflation, wage growth, supply constraints) that might explain the upward price trend despite rising interest rates.
Perform a correlation analysis between interest rates and lagged median sale prices over different time windows.
2. Interest Rate and Total Sales Over Time (Graph 2)
Analysis: This graph compares interest rates (blue) with total sales (green) over time. The sales volume appears to fluctuate more frequently than the interest rates, and both seem to move in tandem at some points, such as around 2021-2022 when interest rates dropped, and sales spiked.

My Interpretation: Total sales seem to respond to changes in interest rates, with sales rising when interest rates are lower. However, the sales fluctuations are more pronounced, possibly due to seasonal or other market-specific factors.
Expansion Ideas:

Explore the seasonal effects in total sales. For example, by decomposing the total sales series into trend and seasonal components using time series decomposition techniques.
Add shaded areas or markers indicating major policy changes, economic events, or housing market interventions that might explain some of the fluctuations.
Calculate and visualize the year-over-year percentage change in sales and interest rates to highlight significant trends.
3. Sales Count and Transaction Value Over Time (Graph 3)
Analysis: This graph shows sales count (blue) and total transaction value (orange) over time. Both series show cyclical patterns, with notable peaks and valleys. The two variables seem to move together, although total transaction value appears more volatile.

My Interpretation: While sales count and transaction value tend to move together, the transaction value’s fluctuations suggest that individual transaction sizes may vary more significantly. For instance, when transaction value spikes without a corresponding increase in sales count, this could imply an increase in the average sale price.
Expansion Ideas:

Compute and plot the average transaction value over time by dividing total transaction value by sales count.
Overlay a rolling average to smooth out the series and highlight longer-term trends in both sales count and transaction value.
Perform regression analysis to quantify how much of the transaction value variation is explained by changes in sales count versus other factors (e.g., changes in average prices, economic conditions).




