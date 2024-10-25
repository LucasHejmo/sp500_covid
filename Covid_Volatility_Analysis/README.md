Comparing Sector Performance Pre- and Post-COVID: A Study of the S&P 500

Project Overview

This project analyzes the performance of four key sectors in the S&P 500: Technology, Healthcare, Energy, and Financials, comparing their behavior before, during, and after the COVID-19 pandemic. It examines the volatility, resilience, and risk-return relationship across these three periods to determine the most stable and volatile sectors.

Sectors & ETFs: 
Technology Sector (XLK),
Healthcare Sector (XLV),
Energy Sector (XLE),
Financials Sector (XLF)

Date Ranges: 
Pre-COVID: 01-01-2017 to 31-12-2019, 
COVID: 01-01-2020 to 31-12-2021,
Post-COVID: 01-01-2022 to 31-12-2023

Repository Structure

snp_ruprekha has the following folders and files

Resources Folder: Contains four CSV files with historical data for each sector, including open, high, low, close, and volume.

volatility.ipynb: The primary Jupyter notebook containing the script for analysis.

output_data Folder: Contains output images (PNG) from the analysis, such as box plots, scatter plots and bar charts.

Volatility_analysis_Ruprekha1.pdf : This file contains detailed analysis of the data.

Technologies used:
Jupyter notebook,
Git,
Alpha Vantage API

Python Libraries Used:

Pandas,
Matplotlib,
Script,
Bumpy,
scikit-Learn,
linregress from scipy.stats,
Requests

Data Exploration & Methodology:

Data Extraction: Data is collected from Alpha Vantage using the provided API, which is then saved in CSV format.

Data Preparation:

CSVs are loaded into Pandas DataFrames, and the relevant date ranges are filtered (Pre-COVID, COVID, Post-COVID).

Daily percentage changes in returns are calculated.

Monthly averages and standard deviations of returns are computed.

The calculated monthly statistics are combined into a single DataFrame.

Summary Statistics:
For each sector, the mean, median, standard deviation, and variance of returns are calculated and compared across Pre-COVID, COVID, and Post-COVID periods.
Visualizations:

Box Plot:
Visualizes the distribution of sector returns during the COVID period.
The Energy (XLE) sector shows the highest volatility, indicated by long whiskers and numerous outliers.
The Financials (XLF) sector follows in volatility but with fewer outliers.
Technology (XLK) and Healthcare (XLV) were the most stable, with Technology exhibiting the highest median returns during COVID.

Multi Bar Chart:
Energy consistently showed the highest volatility across all timeframes, while Healthcare was the most stable.
During COVID, Energy was the most volatile, followed by Financials, Technology, and Healthcare.
Energy's volatility fluctuated greatly across all timeframes, reflecting its sensitivity to market conditions.
In contrast, Healthcare's volatility remained stable, demonstrating its resilience and consistent performance throughout both stable and turbulent periods.

Risk vs. Return Correlation Graphs:
No strong or positive relationship was observed between risk and return for these sectors during the COVID period.
Both the Financial and Technology sectors exhibited a weak negative correlation between risk and return.

Conclusion:

Energy (XLE) was the most volatile sector during the COVID period, reflecting high uncertainty.
Healthcare (XLV) and Technology (XLK) were the most stable sectors, with Technology showing the highest median returns.
There was no significant correlation between risk and return for any sector during the COVID period, highlighting the unpredictability of the market during this time.








