[Think Stats Chapter 3 Exercise 1](http://greenteapress.com/thinkstats2/html/thinkstats2004.html#toc31) (actual vs. biased)

Question:
Something like the class size paradox appears if you survey children and ask how many children are in their family. Families with many children are more likely to appear in your sample, and families with no children have no chance to be in the sample.

Use the NSFG respondent variable numkdhh to construct the actual distribution for the number of children under 18 in the respondents' households.

Now compute the biased distribution we would see if we surveyed the children and asked them how many children under 18 (including themselves) are in their household.

Plot the actual and biased distributions, and compute their means.

Code:
resp = nsfg.ReadFemResp()
pmf = thinkstats2.Pmf(resp.numkdhh, label='numkdhh')
biased = BiasPmf(pmf, label='biased')

thinkplot.Pmfs([pmf, biased])
thinkplot.Config(xlabel='Number of children', ylabel='PMF')

pmf.Mean()
biased.mean()

Answer:
actual mean = 1.024205155043831
biased mean = 2.403679100664282

The actual mean number of children per family is 1.02, which takes into account families that do not have children. The actual distribution is skewed heavily towards 0, meaning that most families have 0 children, and as number of children increases, the frequency decreases.

The biased mean number of children per family is 2.40, which takes into account only the families that have children and exhibits a normal distribution.

When comparing the actual and biased means and their distribution, it can be observed that most families do not have children, but for those that do have children, most have 2.40.
