# **Sector Performance Analysis During COVID-19**

## **Overview**
This project analyzes the performance of four major sectors during the COVID-19 pandemic. Using historical data from **2017 to 2023**, the analysis focuses on key events related to COVID-19 to understand their impact on the Technology (XLK), Healthcare (XLV), Energy (XLE), and Financial (XLF) sectors.

## **Key Objectives**
- Assess how significant COVID-19-related events impacted market performance.
- Compare the average sector performance across different pandemic periods.
- Use statistical analysis to identify the significance of these impacts.
- Visualize the sector trends through various charts to provide insights.

## **Data Source**
Data was collected using the **Alpha Vantage API**, covering daily stock data for the four sectors:
- **Technology (XLK)**
- **Healthcare (XLV)**
- **Energy (XLE)**
- **Financial (XLF)**

The data spans from **2017 to 2023** and includes analysis on periods defined by key COVID-19 events.

## **Key Events Analyzed**
1. **Wuhan Lockdown**: January 23, 2020
2. **COVID-19 Pandemic Declaration**: March 11, 2020
3. **Initial US Lockdowns**: March 15, 2020
4. **Vaccine Trials**: June 1, 2020
5. **Second COVID-19 Wave**: October 1, 2020
6. **Vaccine Rollout**: December 15, 2020
7. **COVID Lockdown End**: July 1, 2021

## **Event Date Sources**
1. **Wuhan Lockdown (January 23, 2020)**: [BBC News - Wuhan Coronavirus Lockdown](https://www.bbc.com/news/world-asia-china-51217455)
2. **COVID-19 Pandemic Declaration (March 11, 2020)**: [World Health Organization - WHO Declares COVID-19 a Pandemic](https://www.who.int/news/item/11-03-2020-who-announces-covid-19-outbreak-a-pandemic)
3. **Initial US Lockdowns (March 15, 2020)**: [The New York Times - U.S. Braces for Shutdowns](https://www.nytimes.com/2020/03/15/world/coronavirus-live.html)
4. **Vaccine Trials (June 1, 2020)**: [Nature - COVID-19 Vaccine Trials Begin](https://www.nature.com/articles/d41586-020-01549-z)
5. **Second COVID-19 Wave (October 1, 2020)**: [CNN - Second Wave of COVID-19 Cases](https://www.cnn.com/2020/10/01/health/covid-second-wave/index.html)
6. **Vaccine Rollout (December 15, 2020)**: [Reuters - First COVID-19 Vaccines Administered](https://www.reuters.com/article/us-health-coronavirus-vaccines-rollout-idUSKBN28P1BF)
7. **COVID Lockdown End (July 1, 2021)**: [Reuters - Lifting of COVID-19 Restrictions](https://www.reuters.com/world/us/most-us-states-lift-covid-restrictions-2021-07-01/)

## **Methodology**
1. **Data Collection**:
   - Data was fetched from Alpha Vantage API.
   - CSV files were generated and processed for each sector to focus on the relevant time periods.
2. **Data Analysis**:
   - Calculated average monthly and specific period returns for each sector.
   - Conducted paired t-tests for each key event to identify statistically significant impacts 60 days before and after the event.
   - Applied ANOVA analysis to compare differences across sectors.
3. **Visualization**:
   - Time series annotated line chart to show sector trends.
   - Heatmap to visualize sector performance across key periods.
   - Grouped bar charts for a comparative analysis of sectors before, during, and after key events.

## **Statistical Analysis**
- **Paired T-Tests**: Applied to identify significant changes in sector performance around key events.

## **Technologies Used**
- **Python**: Data processing and analysis.
  - Libraries: `Pandas`, `Matplotlib`, `NumPy`, `SciPy`, `Requests`
- **Jupyter Notebook**: For interactive data exploration and visualization.
- **Git**: Version control.
- **Alpha Vantage API**: For fetching historical stock data.


