![](itu.png)



# EXPLAINING ISTANBUL HOUSING PRICE WITH DOMINANT INDICATORS & FORECASTING UNIT PRICES CHANGE




<center>Alparslan YARIKTAS</center>
<center>516171003</center>




### Introduction


#### Problem Question


1. How The Economic Indicators Affect on Housing Unit Price at Istanbul?

2. Which indicators more dominant on the prices?

3. What is the equation for Istanbul Unit Housing Price?

4. What will be the housing price for 6 months?


#### Literature Review


- The construction industry and other related sub industries are the most crucial aspects of the economy The
Turkish housing industry has achieved fast growth in the past fifteen years The macroeconomic importance of the
construction industry arises from its multiplier effect It sets 250 sub industries in motion with impacts on both
growth and employment.


- Housing and related interests make up a significant portion of the construction industry in our country. The industry’s growth rate is influenced by booms/stagnation observed in housing demand and sales. 
The industry’s sensitivity to the total national growth is also high.



- As well the price of a home in the housing sector is determined by the balance of housing supply and demand In the short term, the supply of housing is for the most part fixed, meaning that the main variable in determining housing prices is the rise or decline in demand Consequently, in the short term, rising demand for housing causes prices to increase and declining demand causes them to fall.


***







In this study Section - 1 includes "The Regression Analysis" to explain the dependent variable which is **Unit Housing Price in Istanbul** with independent variables below in the table and tried to find **the highest and most effective model** that explaining unit housing price.
In Section B, "The ARIMA Analysis" used for forecasting the "Housing Price Changes In Istanbul" for six months. The summary of study as in the below following chart.


 
 

**Section 1 - Cross Section**            | **Section 2 - Time Series**
-------------------------------------    | -----------------------------------
Regression Analysis                      | Auto Regressive Integrated Moving Average Analysis
Explaining Istanbul Housing Unit Price   | Forecasting Istanbul Housing Price's Change Next Month

***
 

Some variables and description in the below chart.
 



**VARIABLES**    | **DESCRIPTION**
-----------------|--------------------------------------------
**DATE**         | Monthly Date from 2013 to 2019
**IST_RPPI**     | Istanbul Residential Property Price Index
**IST_PRC**      | Istanbul Housing Unit Price TL/m²
**IST_CNST_PRMT**| Construction Permits
**IST_OCCP_PRMT**| Occupational Permits
**MG_RT**        | Mortgage Credit Rates
**IST_FGR_SL**   | Istanbul Housing Sales to Only Foreigners 
**IST_PRP_SL**   | Istanbul Total Housing Sales
**IST_MRTG_SL**  | Istanbul Housing Sales by Using Mortgage Loan
**CNSTR_TRST**   | Construction Trust Index
**IST_CPI**      | Istanbul Consumer Price Index
**TR_PPI**       | Turkey Producer Price Index
**USD_RT**       | USD Buying Exchange Rate
**RNT_CPI**      | IST Rent Consumer Price Index
**NEMP_RT**      | Unemployment Rate



 
 **Notes : IST_CNST_PRMT - IST_OCCP_PRMT forward some different periods 2,3,4,6,9 etc.**




***



For the reason why using both *Price Index* and *Unit Prices* main purpose of the using both Price Index and Prices on the data set in order to see the correlation between Monthly Property Price Index and Unit Prices and cross check our observations.\
It can easily expect the correlation coefficient aproximately ~ 99%
The main value of Housing Prices Index and Unit Prices would be the expecting correlation coefficient which is approximately 0.96 but the monthly percentage changes between them wouldn't be the bigger than 80%.

This study also prove this on the next paragraphs.




[Details](https://github.com/alpyts/AHV "Automatic Housing Valuation")
