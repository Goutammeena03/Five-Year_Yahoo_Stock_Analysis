# Yahoo Stocks Analysis (2019-2024)

This repository contains an in-depth analysis of Yahoo Stocks over the past 5 years, focusing on key indicators and market trends. The analysis leverages moving averages, correlation metrics, and historical market events to provide insights into stock movements.

### Key Insights
##### Moving Averages as Indicators

1. The 50-day moving average (DMA) and 200-day moving average (DMA) are reliable indicators of stock movement.
2. Bullish Trend: When the closing price is above both the 50 and 200 DMA, the stock is typically in an uptrend.
3. Bearish Trend: Conversely, if the closing price is below these DMAs, the stock is usually on a downtrend.
4. Trend Reversal Points: Points where the 50 and 200 DMAs intersect often signal market trend reversals (e.g., high to low or low to high).
   
##### COVID-19 Impact
The significant dip in March 2020 is a clear indicator of the COVID-19 market crash, a historical downturn impacting global markets.

![Screenshot 2024-05-31 165324](https://github.com/Goutammeena03/yahoo_stockprice_prediction/assets/125290702/915ea3fe-240f-4dd0-a474-6a5741742578)

##### Correlation and Collinearity
1. The closing price has a very high correlation with most variables except for the volume.
2. There is strong multicollinearity among variables, suggesting interdependencies.

![Screenshot 2024-05-31 165433](https://github.com/Goutammeena03/yahoo_stockprice_prediction/assets/125290702/f97f6a15-296c-48da-be78-ab588360a6e6)

##### Modeling Insights
1. While achieving a good R² score and coefficients is positive, the high correlation (~1) among variables indicates potential pitfalls.
2. It's essential to be cautious when fitting models based on these highly correlated parameters in real-life scenarios.
   
![Screenshot 2024-05-31 172833](https://github.com/Goutammeena03/yahoo_stockprice_prediction/assets/125290702/58b09a7c-35d8-4228-a33f-e575a8e8bbac)

### Repository Contents

1. Data: Contains the historical stock data used for the analysis.
2. Notebooks: Jupyter notebooks detailing the analysis process, including data cleaning, visualization, and statistical modeling.
3. Reports: Summary reports highlighting the key findings and insights.
4. Images: Visualizations and charts illustrating the stock trends and analysis results.

### Discussion Points
1. Moving Averages: How effective are DMAs in predicting market trends?
2. COVID-19 Impact: How did the market crash influence your investment strategies?
3. Modeling Challenges: Experiences with multicollinearity in financial modeling.
   
### How to Use
1. Clone the repository: git clone https://github.com/Goutammeena03/yahoo_stockprice_prediction.git
2. Navigate to the project directory: cd yahoo-stocks-analysis
3. Open and run the Jupyter notebooks to explore the analysis.

Let's discuss and explore these insights together!

### License
This project is licensed under the MIT License - see the LICENSE file for details.
