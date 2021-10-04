# VBA_Stock Analysis

## Overview of Project
This code is made to analyze the yearly summary of stock market. The main idea is to check to action´s volume of yearly trading and the yearly return. This Macro present two option of analysis, this is to be able to compare two processes that do the same, but one of it with less computational effort which means less time running.


## Results

### Coding
The flow of the code is simple. For each row the code analyzes the rows and sum all the volumes per action so we can have the total volume. For the return rate we just take the first data as the initial price and the last one for final price. 

<img src="https://render.githubusercontent.com/render/math?math=Return =\frac{Ending Price}{Inicial Price}-1">

The interesting part of the code is the two options of analysis. To see it in a simple way this code needs to check every row to save the data of each one. In the first code is a for loop of each row looking for a specific action, so the computer runs all rows for each action. The second one store the data without looking for a specific action so the for loop just check the whole rows once.
For 2017 took 1 second and with the new code last for 0.28 seconds

! [Timer_2017](VBA_Challenge_2017.png)

For 2017 took .09 seconds and with the new code last for 0.29 second

! [Timer_2018](VBA_Challenge_2018.png)


### 2017 & 2018
For 2017 the only action with negative return was TERP, the best action to invest was DQ and SEDG.
On the other hand, after the good year 2017 almost every action has negative return rate during 2018, except for ENPH and RUN. DQ was one of the biggest looser, so it was a good investment option but in 2018 was a bad call. TERP remains as a looser action, so I don’t recommend it.


## Summary

Refactor a code maybe see simple and for this case was not so representative because of the complexity of this analysis. But for other codes with higher computational complexity will allow the researcher or data analyst to save time, improve the efficiency and have a aesthetic code.
In this case the code help use to check least time the rows and we improve the efficiency of the computer. This same idea applied to a bigger data set will show better results. So we can conclude that refactor this code will show better results as the data set gets bigger



