[Think Stats Chapter 2 Exercise 4](http://greenteapress.com/thinkstats2/html/thinkstats2003.html#toc24) (Cohen's d)

Question:
Using the variable totalwgt_lb, investigate whether first babies are lighter or heavier than others.

Compute Cohen’s effect size to quantify the difference between the groups. How does it compare to the difference in pregnancy length?

Code:
CohenEffectSize(firsts.prglngth, others.prglngth)
CohenEffectSize(firsts.totalwgt_lb, others.totalwgt_lb)

Answer:

Prglngth diff first - others: 0.028879044654449883
Totalwgt_lb first - others: -0.088672927072602006

Cohen's Effect Size between the total weight of first born babies to all other babies is -.088. This means that the first born baby mean total weight is -.088 standard deviations smaller than the other baby mean total weight. This is close to an opposite effect size between pregnancy length for first born and other babies, which was .028, indicating that the mean pregnancy lengths for first borns is .028 standard deviations larger than that of lengths for other babies. Overall, the data is indicating a potential for pregnancy lengths to be longer and and weights smaller for first borns, however the effect size is very small.