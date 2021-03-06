# Stock Analysis
## Overview of Project
### Purpose
The purpose of this project is to help Steve, a recent finance graduate, analyze a large amount of green energy stocks in an effort to better assist his first investment clients, his parents. Steve’s parents have done no background research and instead invested all their money into DAQO New Energy Corp, ticker ‘DQ’, due to its emotional significance for them. My job is to help Steve analyze these excess green energy stocks so he can present the findings to his parents and hopefully diversify and expand the allocation of their funds. We will be analyzing the data set by running macros in VBA, a Microsoft Office programming language we use to interact with Excel. VBA is a high-tech tool that can read and write worksheets, interact with them, and run complex analyses. Our development of automated analyses on these stocks allows Steve to reuse it with any stock which reduces the potential for accidents and errors. 
## Results
### Analysis of Findings
It is blatantly obvious from the overview images below that stock performance in 2017 was much better than that in 2018. Perhaps there was a crash or dip in the market in 2018 in this scenario. Almost all returns were positive in 2017 except for one. TERP appears to be the least successful stock ticker being the only one with a negative outcome in 2017 and continuing to stay negative in 2018. 

![2018_Stock_Overview](https://github.com/CristinaCod/stock-analysis/blob/main/Resources/2018_Stock_Overview.png)
![2017_Stock_Overview](https://github.com/CristinaCod/stock-analysis/blob/main/Resources/2017_Stock_Overview.png)

Based on the findings, the next step for Steve may be to advise his parents to invest in ENPH or RUN as those were the only two tickers with a continuous positive return from 2017 through 2018. 

Another aspect that is to be expected but important to note is the fact that the run times vary every time you run the analysis on the stocks. We are working with a machine here and lag times are to be expected however the variance between times is so miniscule I do not find it to be a significant number. As will be discussed below the execution time is also slightly greater when using the refactored code compared to the original however, again I do not find the difference to be of great significance. 

![VBA_Challenge_2017](https://github.com/CristinaCod/stock-analysis/blob/main/Resources/VBA_Challenge_2017.png)
![VBA_Challenge_2018](https://github.com/CristinaCod/stock-analysis/blob/main/Resources/VBA_Challenge_2018.png)

## Summary
### Refactoring Code 
  The purpose of refactoring code in general is to help improve the efficiency of said code. Many times, the first code written isn’t the most efficient, pretty, or concise. Refactoring helps to hopefully create the most effective code possible. The most important thing to note in refactoring is that while the code may be more organized, the function of it stays the same. Refactoring simply changes the structure of the code not its behavior. And just like anything else it has pros and cons. 
  
  Some advantages of refactoring code include as mentioned above the efficacy of it. Refactoring helps make code easier to understand for future use either by yourself or for other users. Most times refactoring involves making the code shorter by using fewer steps thus improving the logic of the code as it takes up less memory and runs faster.   
  
  Some disadvantages of refactoring include the fact that while you are potentially improving the code, you haven’t changed its function, and therefore potentially wasted extensive valuable time on the same code that could’ve been spent on other projects. It’s possible that you may spend more time refactoring your code than you spent writing the original. Another potential disadvantage is the fact that any time you change code you run the risk of introducing bugs to it. Spending time refactoring a perfectly good code could actually do more harm than good if bugs are then introduced. 
### Refactoring VBA Script
  Much of the challenge starter code paralleled that of the original code showing the versatility of it. The advantage of this is that the original provided a good line of guidance when writing the refactored code. An important thing to note is while working through the Module, prior to the Challenge, when we ran the “AllStockAnalysis” we were specifically doing so only for the year of 2018 not 2017 included. Obviously, it would be easy to run the original code for 2017, we would simply have to change the year value in the code, in my Module 4 within VBA, to 2017 as opposed to 2018 like it is currently set. 
  
  Disadvantage wise, I did notice that I spent much more time refactoring the code than I did on the original. This could also be in part that something kept going wrong where my ticker 2 “CSIQ” kept disappearing and changing to the name of ticker 11 “VSLR”, thus effecting my outcomes. So that was a problem that stumped myself and my tutor for quite some time. This could mean that a bug was introduced at some point in the refactoring process that I ultimately successfully worked through. When running my final analyses, I did unexpectedly find that my time was longer using the refactored code compared to the original. However, it was only greater by a few milliseconds so the significance of that is debatable. 
  
  Despite these challenges, working through this code extensively was beneficial in the long run. It helped me figure out how to better write different lines of script and increased my understanding of the jargon itself. Both of which I previously mentioned are advantages of refactoring code in general. 
