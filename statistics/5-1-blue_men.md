[Think Stats Chapter 5 Exercise 1](http://greenteapress.com/thinkstats2/html/thinkstats2006.html#toc50) (blue men)


Question: 
In order to join Blue Man Group, you have to be male between 5’10” and 6’1” (see http://bluemancasting.com). What percentage of the U.S. male population is in this range? Hint: use scipy.stats.norm.cdf

Code:
low = dist.cdf(177.8)    
high = dist.cdf(185.4)   
dif = high-low
dif

Answer:
34% of the U.S. male population is between 5'10" and 6'1".