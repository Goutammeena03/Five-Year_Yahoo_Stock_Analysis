# Yahoo Stocks Analysis (2019-2024)

This repository contains an in-depth analysis of Yahoo Stocks over the past 5 years, focusing on key indicators and market trends. The analysis leverages moving averages, correlation metrics, and historical market events to provide insights into stock movements.

### Key Insights
###### Moving Averages as Indicators

The 50-day moving average (DMA) and 200-day moving average (DMA) are reliable indicators of stock movement.
Bullish Trend: When the closing price is above both the 50 and 200 DMA, the stock is typically in an uptrend.
Bearish Trend: Conversely, if the closing price is below these DMAs, the stock is usually on a downtrend.
Trend Reversal Points: Points where the 50 and 200 DMAs intersect often signal market trend reversals (e.g., high to low or low to high).
COVID-19 Impact
The significant dip in March 2020 is a clear indicator of the COVID-19 market crash, a historical downturn impacting global markets.
Correlation and Collinearity
![Screenshot 2024-05-31 165324](https://github.com/Goutammeena03/yahoo_stockprice_prediction/assets/125290702/915ea3fe-240f-4dd0-a474-6a5741742578)

The closing price has a very high correlation with most variables except for the volume.
There is strong multicollinearity among variables, suggesting interdependencies.
Modeling Insights
![Screenshot 2024-05-31 165433](https://github.com/Goutammeena03/yahoo_stockprice_prediction/assets/125290702/f97f6a15-296c-48da-be78-ab588360a6e6)

While achieving a good R² score and coefficients is positive, the high correlation (~1) among variables indicates potential pitfalls.
It's essential to be cautious when fitting models based on these highly correlated parameters in real-life scenarios.
![Screenshot 2024-05-31 172833](https://github.com/Goutammeena03/yahoo_stockprice_prediction/assets/125290702/58b09a7c-35d8-4228-a33f-e575a8e8bbac)

### Repository Contents
Data: Contains the historical stock data used for the analysis.
Notebooks: Jupyter notebooks detailing the analysis process, including data cleaning, visualization, and statistical modeling.
Reports: Summary reports highlighting the key findings and insights.
Images: Visualizations and charts illustrating the stock trends and analysis results.

### Discussion Points
Moving Averages: How effective are DMAs in predicting market trends?
COVID-19 Impact: How did the market crash influence your investment strategies?
Modeling Challenges: Experiences with multicollinearity in financial modeling.
### How to Use
Clone the repository: git clone https://github.com/your_username/yahoo-stocks-analysis.git
Navigate to the project directory: cd yahoo-stocks-analysis
Open and run the Jupyter notebooks to explore the analysis.
Let's discuss and explore these insights together!

### License
This project is licensed under the MIT License - see the LICENSE file for details.
