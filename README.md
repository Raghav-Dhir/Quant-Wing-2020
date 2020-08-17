# Quant-Wing-2020
This is my submission for the Quant Assignment.  
Some notes regarding the answers-  
Ans1.  
The Binomial Asset Pricing Model has been coded for a random option. The sigma i.e volatility has been hard coded here but can be easily be calculated for a particular asset.  
Ans2.  
Simple Pairs Trading strategy is applied and the selected stocks are some of the high market cap stocks of NASDAQ index.  
More sophisticated techniques like SVM, Linear Regression could have been used for the indication of buy/sell signal (-1/1).  
I divided the testing and training data by 30 and 70 percent respectively and both were backtested.  
The ratio was normalised using the 60 and 5 day moving averages.  
Buy and sell signals are also labelled.  
Ans3.  
A portfolio was made out of 5 most uncorrelated stocks according to their daliy returns.  
Basically, Markowitz Portfolio Theory has been coded and the desired portfolio has been marked.(It does not lie exactly on the efficient frontier maybe due to some random errors in implementing the theory)   
