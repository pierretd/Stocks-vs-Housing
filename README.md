# Stocks-vs-Housing
How are the stock market and housing costs related?

![Stocks vs Cribs](https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcS22eEbCxfjBn3cobw04MFxGgGZNfTIFcaRupBNf8LWxAfpznBA&usqp=CAU)

## Introduction


This data set contains data from the Yale Department of Economics. Specifically the Real Building Cost Index(RBCI) and the S&P Composite Index(COMP) from 1890 to 2019. 

RMBI represents the costs in the building construction market in the United States. COMP represents the composite index of the top 500 public companies listed in the United States.

Understanding the relationship between the two can help real estate developers plan construction or investors predict the market. If RBCI and COMP has a positive relationship, Real Estate developers can expect thier costs to rise as the economy grows. Investors also know that companies that are in real estate will face higher costs for development. If RBCI and COMP have a negative relationship, both investors and Real Estate developers can expect the opposite. If the two features have no relationship, we can assume that there is no relationship between the growth of the economy and prices in the construction market and must search further for correlations.


Our task is to use RMBI to better predict the COMP and to determine if we can gain a market edge by understanding their relationship.

## Null Hypothesis

## Dataset overview

# Data Sets

The data is contained in two files:

* RBCI.csv - Historical Housing Market Data - Real Building Cost Index(https://www.quandl.com/data/YALE/RBCI-Historical-Housing-Market-Data-Real-Building-Cost-Index)


* COMP.csv - S&P Composite (https://www.quandl.com/data/YALE/SPCOMP-S-P-Composite)

Here is the schema and explanation of each variable in the files:

**RBCI.csv**
* Distributed yearly
* Date (object) - Date - dd/mm/yyyy
* Cost Index (float64) - Measures the costs in the building construction market in the United States


**COMP.csv**
Distributed daily
* Year (object) - Date - dd/mm/yyyy
* S & P Composite (float64) - Measures the composite index of the top 500 companies listed in the United States

## Methodology
The RBCI is distributed yearly while the COMP is a daily metric. I used the yearly average of the S & P 500 to make the metrics congruous. I then standardized the data to give each feature an average of 1 and standard deviation of 0. 


## Results

I fail to reject the null hypothesis. Because....
