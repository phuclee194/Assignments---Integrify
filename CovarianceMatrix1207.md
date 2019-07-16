2. Define Bias of an estimator

An estimator is a statistic that estimate some fact about population. 
The quantity that is being estimated is called the estimand.

Estimators can be described in several ways:
Biased: a statistic that is either an ocerestimate or an underestimate
Efficient: a statistic with small variances
Invariant: statistics that are not easily changed by transformations
Shrinkage: a raw estimate that's improved by combining it with other information
Sufficient: a statistic that estimates the population parameter
Unbiased: an accurate statistic that neither underestimates nor over estimates




Quantile Use, SEM


import numpy as np
import statsmodels.api as sm
import pylab


test = np.random.normal(20,5, 1000)

sm.qqplot(test, loc = 20, scale = 5, line = '45')
pylab.show()

1. Explain why the points don't lie on the line y = x

2. Explain what is standard error of the mean
The standard error of the mean is the standard deviation of the mean. It is a method used to estimate
the standard deviation of a sampling distribution. 

\begin{align}
\sigma & =\frac{\sigma}{\sqrt{N}

3. Simulate SEM example using NumPy
4. 