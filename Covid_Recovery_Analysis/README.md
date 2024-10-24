# Group-Project-1-Covid-Recovery
Project Title: Comparing Sector Performance Pre- and Post-COVID: A Study of the S&P 500

Project Description:
This project aims to compare and contrast the performance of four major sectors within the S&P 500—Technology, Healthcare, Energy, and Financial—before and after the COVID-19 pandemic. The analysis will highlight the similarities and differences between the sectors and draw conclusions about which sectors were more resilient or volatile during these periods. 

The relevant data was fetched via the Alpha Vantage API and then cleaned to reflect the time period in question of January 2017 till December 2023.

The appended analysis however specifically focuses on the key differences in the recovery patterns of the Financial, Healthcare, Technology and Energy sectors in the direct aftermath of COVID. Therefore, the data was cleaned and filtered for January 2020 - December 2021, as these dates best reflect the time period in question, where the initial crash due to COVID lockdowns and recovery during the COVID period can be visualised and analysed.

Some initial line charts were made for the individual sectors, where the closing price is plotted across both the entire 2017 - 2023 and the focused 2020 - 2021 time periods. These were plotted for all sectors, simply to sense-check the data pulled from the API, the accuracy of the coding to clean and filter the data and to gain a general understanding of the industry trends at a glance.

Ultimately, the individual charts for the time period in question were combined into the 'Stock Price Recovery - COVID-19 Period (2020-2021)' chart. This chart crucially presents the performance of all 4 sectors by showcasing the pre-crash closing prices at the start of the year, the COVID crash in the initial lockdown stages, and the recovery process till the end of 2021. These elements across this time period form the basis of the study.

Next the % returns were calculated for the 4 sectors, but these could not be effectively plotted in a daily or even weekly format. Therefore, Monthly Average % returns were calculated and plotted in the 'Monthly Average % Returns of Sectors - COVID-19 Period (2020-2021)' graph. This gave an indication of volatility in the different sectors, where the Energy Sector stood out.

Further analysis was done on the volatility using a box plot for the % returns and a heatmap of the standard deviation of % returns, both of which highlighted the Energy sector as an outlier in terms of volatility.

Next the 'Cumulative Returns During the Recovery Period' chart was created to showcase the cumulative % returns of the 4 sectors, across the same time period. This is a useful chart for showcasing which sector grew the most during the recovery period, and thus had the strongest recovery in the aftermath of COVID.

A correlation analysis was done to better showcase the recovery patterns of the individual sectors. It shows how closely correlated the recovery of individual sectors may be, due to overlapping factors. For example, the Energy and Financial sectors were found to be closely correlated, owing to macroeconomic factors such as increased demand for energy due to increased economic activity. Healthcare and Technology were also found to be strongly correlated, in line with the increased investment in health-tec initiatives and digital health solutions during the pandemic and lockdowns.

Finally, though a regression analysis was also done, the results were deemed inconclusive due to the limitations of the dataset. Considering this is stock market data, there a number of factors not captured by the current size of the dataset, posing limitations for a regression analysis. This is also the most likely reason the p-value of the regression model was not statistically significant.

Therefore, the correlation analysis, volatility heatmap, cumulative returns and the other charts are much better indicators of how the different sectors performed in the aftermath of COVID.