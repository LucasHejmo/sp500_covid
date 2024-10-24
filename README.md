# **Sector Performance Analysis During COVID-19**

## **Overview**
This project analyzes the performance of four major sectors—**Technology (XLK)**, **Healthcare (XLV)**, **Energy (XLE)**, and **Financial (XLF)**—within the S&P 500 during the COVID-19 pandemic. Using historical data spanning from **2017 to 2023**, the analysis focuses on understanding sector behaviour before, during, and after COVID-19, highlighting which sectors were most resilient or volatile during these periods.

## **Key Objectives**
1. Assess how significant COVID-19-related events impacted market performance.
2. Compare the average sector performance across different pandemic periods.
3. Visualize sector trends through various charts to provide insights.
4. Conduct detailed statistical analysis on volatility, risk, recovery patterns, and key differences across sectors.

## **Data Source**
Data was collected using the **Alpha Vantage API**, covering daily stock data for each sector. The analysis specifically focuses on periods defined by key COVID-19 events:
- **Technology (XLK)**
- **Healthcare (XLV)**
- **Energy (XLE)**
- **Financial (XLF)**

## **Key Events Analyzed**
1. **Wuhan Lockdown**
2. **COVID-19 Pandemic Declaration**
3. **Initial US Lockdowns**
4. **Vaccine Trials**
5. **Second COVID-19 Wave**
6. **Vaccine Rollout**
7. **COVID Lockdown End**

### **Event Date Sources**
- Wuhan Lockdown (January, 2020): [BBC News](https://www.bbc.com/news/world-asia-china-51217455)
- COVID-19 Pandemic Declaration (March, 2020): [WHO Announcement](https://www.who.int/)
- Initial US Lockdowns (March, 2020): [The New York Times](https://www.nytimes.com/)
- Vaccine Trials (June, 2020): [Nature Journal](https://www.nature.com/)
- Second COVID-19 Wave (October, 2020): [CNN Report](https://www.cnn.com/)
- Vaccine Rollout (December, 2020): [Reuters Report](https://www.reuters.com/)
- COVID Lockdown End (July, 2021): [Reuters Report](https://www.reuters.com/)

## **Methodology**
1. **Data Collection**:
   - Historical stock data was fetched using the Alpha Vantage API.
   - CSV files were created for each sector to narrow down relevant time periods.
   
2. **Data Analysis**:
   - **Monthly Averages**: Calculated average monthly returns for each sector.
   - **Volatility Analysis**: Evaluated standard deviations and risk to identify volatility across sectors.
   - **Risk and Return**: Analyzed whether high volatility translated to higher returns during the pandemic.
   - **Sector Comparisons**: Compared average sector performance before, during, and after COVID-19.
   - **Recovery Patterns**: Focused on key differences in sector recovery post-COVID.
   - **Correlation Analysis**: Assessed how closely recovery trends in sectors were linked.
   
3. **Visualization**:
   - **Annotated Line Charts**: Show monthly average trends and major events during COVID-19.
   - **Line Charts**: Show an overview of the sectors before, during, and after COVID-19
   - **Heatmaps**: Visualized sector performance using average returns and standard deviations.
   - **Box Plots**: Analyzed the distribution of returns for each sector to highlight volatility.
   - **Grouped Bar Charts**: Compared performance across sectors in pre-pandemic, pandemic, and post-pandemic periods.
   - **Cumulative Returns Charts**: Displayed how each sector grew during the recovery phase.
   - **Scatterplots and Regression**: Showcased trends and correlations between sector recoveries.

## **Data Analysis Insights**
### **Pre-COVID Market Stability**
- From 2017 to 2020, sectors demonstrated varied stability:
  - **Energy** showed high volatility, reflecting sensitivity to external events.
  - **Healthcare** was the most stable, likely due to its essential role during the pandemic.
  - **Technology** showed moderate stability, with steady growth.
  - **Financials** exhibited volatility, but less pronounced than Energy.

### **Volatility During COVID-19**
- The Energy sector had the highest volatility throughout the pandemic, making it the most sensitive to global events.
- The Financial sector followed in volatility, impacted by market uncertainty.
- Technology showed moderate volatility, but demonstrated strong recovery trends post-COVID.
- Healthcare remained the most stable sector, supported by its critical role during the pandemic.

### **Sector Recovery Analysis**
- **Monthly Average % Returns**: Showed volatility trends, with Energy standing out as the most unpredictable.
- **Cumulative Returns**: Highlighted the recovery phase, with Technology and Healthcare leading in post-COVID recovery.
- **Correlation Analysis**: Showed strong links between certain sectors:
  - Energy and Financials were closely correlated, likely influenced by economic recovery factors.
  - Technology and Healthcare also demonstrated a correlation, reflecting increased digital health initiatives during COVID.

### **Statistical Analysis**
- **Paired T-Tests**: Assessed sector performance around key COVID-19 events to identify statistically significant changes.
- **Volatility Heatmaps**: Showcased which sectors were most affected by COVID-19.
- **Box Plots**: Illustrated the spread and outliers in sector returns, with Energy frequently highlighted as an outlier.
- **Scatterplots and Regression Analysis**: While useful for visualizing trends, the regression analysis faced limitations due to the complexity of the stock market data.

## **Technologies Used**
- **Python**: Data processing and analysis.
  - **Libraries**: `Pandas`, `Matplotlib`, `NumPy`, `SciPy`, `Requests`, `StringIO`, `Seaborn`
- **Jupyter Notebook**: For interactive data exploration and visualization.
- **Git**: Version control for collaborative work.
- **Alpha Vantage API**: For fetching historical stock data.

## **Visualizations**
### 1. **Time Series Annotated Line Chart**
   - Annotated line charts displayed monthly average sector performance during the COVID-19 pandemic.
### 2. **Heatmap**
   - Visualized sector performance across key periods to highlight volatility.
### 3. **Grouped Bar Chart**
   - Comparative analysis showing average sector closing prices for each pandemic period.
### 4. **Box Plots**
   - Analyzed sector return distributions to determine the extent of volatility during COVID-19.
### 5. **Cumulative Returns Chart**
   - Displayed sector growth trajectories post-COVID, showing which sectors led the recovery.
### 6. **Correlation Analysis**
   - Highlighted correlations between sectors’ recovery patterns, identifying shared recovery factors.##


## Collaboration

- Lucas Hejmo Jones  (@Lucashejmo):   /During_Covid_Analysis
- Rushad Confectioner  (@Rushad-hub):   /Pre_Covid_Analysis
- Ruprekha Baruah  (@ruprekhab):   /Covid_Volatility_Analysis
- Ammar Samad Khan  (@AmmarK995):   /Covid_Recovery_Analysis



## **License**
### **MIT**

## **How to Run the Project**
### **1. Clone the repository**
   ```bash
   git clone https://github.com/LucasHejmo/sp500_covid.git

   cd sp500_covid

   pip install -r requirements.txt
