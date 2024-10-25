Sector Performance Analysis During COVID-19

Overview

This project takes a closer look at how four key sectors—Technology, Healthcare, Energy, and Financials—performed in the years leading up to and just before the COVID-19 pandemic. By examining historical stock data from 2017 to 2020, we aim to understand how the markets were behaving before COVID hit, and how significant pandemic-related events influenced each sector’s performance.

Key Objectives

	1.	Pre-COVID Market Stability: How were the markets holding up before the pandemic?
	2.	Impact of Key Events: How did major COVID-19-related events affect the sectors?
	3.	Sector Comparisons: Compare the average performance of the sectors from 2017 to 2020.
	4.	Statistical Insights: Use data analysis to identify trends and key drivers behind them.
	5.	Visualization: Use charts and visual tools to uncover and communicate sector trends.

Data Source

We gathered daily stock data for the following sectors using the Alpha Vantage API:

	•	Technology (XLK)
	•	Healthcare (XLV)
	•	Energy (XLE)
	•	Financial (XLF)

The data spans from 2017 through 2020, giving us a comprehensive view of performance leading up to and during the pandemic.

Key Events Analyzed

We’ll focus on events directly related to the pandemic to see how each sector reacted.

Methodology

	1.	Data Collection:
	•	Historical stock data was fetched using the Alpha Vantage API.
	•	CSV files were created for each sector to narrow down relevant time periods.
	2.	Data Analysis:
	•	We calculated the average monthly and event-specific returns for each sector.
	•	Closing prices were tracked to see sector trends over time.
	3.	Visualization:
	•	A dual-axis line chart will show both sector returns and closing prices.
	•	Scatterplots with regression analysis will help us visualize and interpret trends.

Tools & Technologies

	•	Python: Data analysis and processing.
	•	Libraries: Pandas, Matplotlib, NumPy, SciPy, Requests.
	•	Jupyter Notebook: For interactive data exploration and visualization.
	•	Git: To keep track of changes and collaborate.
	•	Alpha Vantage API: To pull historical stock data.
