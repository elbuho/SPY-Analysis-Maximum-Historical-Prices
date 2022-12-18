# SPY Analysis of Maximum Historical Prices
This study intends to explore and study one of the main American indexes Standard & Poor's 500 index (SPY) from the perspective of the breaks of their maximum historical prices over time and see what impact or how a simple strategy of buying every time a price occurs new all-time high and hold the position for one year.

We will see how many breakouts occurred over time and what returns this simple strategy would give in the past. This study is not a backtest, it is simply a statistical study to see if there are any indications that the strategy might work. 

## Prerequisites

* Python 3
* NumPy
* Pandas
* Matplotlib
* Seaborn
* yfinance

## Dataset
We used the yfinance python package to download thehistorical  daily prices of the SPY


* Original variables in the dataset:  

    + Open: Initial price when the market just open
    + High: maximun price of the day
    + Low: lowest price of the day
    + Close: Final price of the day
    + Adj Close: Adjuste price of the close price that consider splits and dividends
    + Volume: Number of transation in a day
    
    


* Variables created to enrich the analysis:  
    + max_high: Each day that SPY reach a new maximun high
    + order: The value is 1 if there is a new maximum or zero otherwise
    + year: We getit from the index of the dataset

## Acknowledgements

* The data for this project was collected using the yfinance package.

## Table of Contents

* Gather the data
* Assess and explore the data
* Clean the data
* Analysis and visualization
    + SPY Adjusted Close Prices plot
    + Number of maximum historical prices per year
    + Plot all series of 250 days after new high

## Conclusion
        

## Summary of Findings

*






