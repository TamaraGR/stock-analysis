# VBA Green Stocks Analysis for the years 2017 and 2018

## Overview of the Project 

This is an analysis of the ![VBA_Challenge](https://github.com/TamaraGR/stock-analysis/blob/main/VBA_Challenge.xlsm) file. In this analysis we are helping a client get information and compare the Total Volume and Yeary Return of various green energy companies' stocks in 2017 and 2018. We designed a VBA macro for applying it to different years (namely, in our analysis, we are using it for the years 2017 and 2018). The VBA macro calculates price change for the said year, change in the percentage of the price for that year and the total volume traded for the same year. For the client's convinienece we have designed buttons inside our AllStocksAnalysis sheet of the mentioned above document to perform general all stocks analysis and refactored all stocks analysis. With the help of this analysis our client can review which stocks have performed better than others. 

## VBA Analysis Results 

### 2017 and 2018 Stock Anaysis Comparison 

*2017 refactored stock analysis image*

![VBA_Challenge_2017](https://github.com/TamaraGR/stock-analysis/blob/main/VBA_Challenge_2017.png)

*2018 refactored stock analysis image*

![VBA_Challenge_2018](https://github.com/TamaraGR/stock-analysis/blob/main/VBA_Challenge_2018.png)

2017 was a pretty good year for the green energy companies' stocks market. As we can see from the image above, all of the stocks had positive returns with the exception of the TERP stock, which had a negative return of -7.2%. DQ and SEDG had the highest returns with 199.4% and 184.5% respectively. 

2018 looks very different from 2017. As we can see from the image above, most stocks had a negative return, except ENPH at 81.9% and RUN at 84.0%. We must note that in 2017 these two stocks scored at 129.5% and 5.5% respectively. The stock that was the lowest in 2017, TERP, was recorded at a negative return of -5%, however, it's the one with least changes in compariosn to all the other stocks analyzed. At the same time, 2017's stocks with highest return rate, DQ and SEDG, scored at -62.6% and -7.8%. 

The analysis of the greenstocks returns for the years 2017 and 2018 doesn't give us enough data to provide our client with adequeate level of detail and forecast/ advice with regards to which stocks to purchase. The recommendation is to look beyond these two years for deeper analysis. 

### General Analysis and Refactored Analysis 

*2017 general stock analysis speed image*

![AllStockAnalysis_2017_Timer](https://github.com/TamaraGR/stock-analysis/blob/main/AllStocksAnalysis_2017_timer.png)

*2018 general stock analysis speed image*

![AllStockAnalysis_2018_Timer](https://github.com/TamaraGR/stock-analysis/blob/main/AllStocksAnalysis_2018_timer.png)

*2017 refactored stock analysis speed image*

![VBA_Challenge_2017_Timer](https://github.com/TamaraGR/stock-analysis/blob/main/VBA_Challenge_2017_timer.png)

*2018 refactored stock analysis speed image*

![VBA_Challenge_2018_Timer](https://github.com/TamaraGR/stock-analysis/blob/main/VBA_Challenge_2018_timer.png)

As you can see from the images above, the calculations execution time ran much faster when ordered through the refactpred script in comparison to the general analysis script. 
In the refactored analysis we are not using the nested for loops. In fact, we are using only three loops, one in 2a, one in 2b through 3d and one in 4. The script for the refactored analysis goes through fewer iterations and therefore allows for less time for calcupations. For further reference to the loops code please see the images of the general script versus the refactored script below. 

*General Code*

![GeneralCode](https://github.com/TamaraGR/stock-analysis/blob/main/GeneralCode.png)

*Refactored Code*

![Refactured_Script_1](https://github.com/TamaraGR/stock-analysis/blob/main/Refactured_Script_1.png)

![Refactured_Script_2](https://github.com/TamaraGR/stock-analysis/blob/main/Refactured_Script_2.png)

## Summary 

**Below is the summary of the performed stocks analysis**

*What are the advantages or disadvantages of refactoring code?*

The advantage of refactoring code is that it becomes more efficient. Not only the calculations run faster, but reading such code is easier, hense it's easier to find a potential bug, catch duplicate and unnecessary code. 

The disadvantage of refactoring code is that the general code is more sequential than the refactored code. It is also possible that one refactores the code incorrectly, and then the code stops performing calculations, which would be to our disadvantage. 

*How do these pros and cons apply to refactoring the original VBA script?*

Refactoring helps us reduce the humber of for loops, which will result in reducing the memory that we need for processing the data calculations. Therefore the speed run time reduces. The con of applying the refactoring to the original VBA script is that it can mess up one's code, so maximum attention is needed. 





