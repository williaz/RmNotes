# FRM
quick, key words, 7, short
## Quantitative Analysis
### 15. Probabilities
After completing this reading, you should be able to:
1. Describe and distinguish between continuous and discrete random variables.
(page 13)
  - A random variable is an **uncertain** quantity/number.
  - An outcome is an **observed value** of a random variable.
  - An event is a single outcome or a set of outcomes.
  - Mutually exclusive events are events that cannot happen at the same time.
  - Exhaustive events are those that include **all** possible outcomes.
  - A probability distribution describes the probabilities of all the possible outcomes for
a random variable.
  - A discrete random variable is one for which the number of possible outcomes can be
**counted**, and for each possible outcome, there is a **measurable** and positive probability.
  - A probability function, denoted p(x), specifies the probability that a random variable is
equal to a specific value.
  - A continuous random variable is one for which the number of possible **outcomes is infinite**,
even if lower and upper bounds exist.


2. Define and distinguish between the probability density function, the cumulative
distribution function, and the inverse cumulative distribution function, (page 15)
  - A probability density function (pdf) is a function, denoted f(x), that can be used to
generate the probability that outcomes of a continuous distribution lie within a particular
**range** of outcomes.
    - pf VS pdf
  - A cumulative distribution function (cdf), or simply distribution function, defines the
probability that a random variable, X, takes on a value **equal to or less** than a **specific value**,
x.
  - inverse
cumulative distribution function can be used to find the value that corresponds to a
**specific probability.

3. Calculate the probability of an event given a discrete probability function, (page 16)
  - A discrete uniform random variable is one for which the probabilities for all possible
outcomes for a discrete random variable are **equal**.

4. Distinguish between independent and mutually exclusive events, (page 19)
  - Independent events refer to events for which the occurrence of one has **no influence** on the
occurrence of the others.
    - P(A | B) = P(A), or equivalently, P(B | A) = P(B)
    - addition rule fo r probabilities: P(A or B) = P(A) + P(B) - P(AB)
  - mutually exclusive events where the joint probability, P(AB), is zero
  
5. Define joint probability, describe a probability matrix, and calculate joint
probabilities using probability matrices, (page 21)
  - When dealing with independent events, the word and indicates multiplication, and the
word or indicates addition.
    - P(A or B) = P(A) + P(B), and P(A and B) = P(A) x P(B)
  - Joint probabilities of independent events can be conveniently summarized using a
probability matrix (sometimes known as a probability table).

6. Define and calculate a conditional probability, and distinguish between conditional
and unconditional probabilities, (page 18)
  - Unconditional probability (i.e., marginal probability) refers to the probability of an event
**regardless of** the past or future occurrence of other events.
  - A conditional probability is one where the occurrence of one event affects the probability of
the occurrence of another event.
  - The joint probability of two events is the probability that they will **both occur**.
  - multiplication rule o f probability: P(AB) = P(A | B) x P(B)
  
### 16. Basic Statistics
After completing this reading, you should be able to:
- statistics is used to refer to data and the methods we use to analyze data.
  - Descriptive statistics are used to summarize the important **characteristics** of large data
sets.
  - Inferential statistics pertain to the
**procedures** used to make forecasts, estimates, or judgments about a **large set** of data on
the **basis of** the statistical characteristics of a smaller set (a **sample**).
- A population is defined as the set of **all possible members** of a stated group.

1. Interpret and apply the mean, standard deviation, and variance of a random
variable, (page 29)
- mean
  - The **arithmetic mean** is the only measure of **central tendency** for which the sum of the
deviations from the mean is zero.
      - To compute the **population mean**, all the observed values in the population are summed
(EX) and divided by the number of observations in the population, N.
      - The **sample mean** is the sum of all the values in a sample of a population, EX, divided
by the number of observations in the sample, n. It is used to make **inferences** about the
population mean
      - mean deviaion = Xi - Xmean; sum == 0
  - The **geometric mean** is often used when calculating investment returns over multiple
periods or when measuring compound growth rates.
  - The geometric mean is always **less than or equal to** the
arithmetic mean, and the difference increases as the dispersion of the
observations increases. The only time the arithmetic and geom etric means are
equal is when there is no variability in the observations (i. e., all observations
are equal).
- The **median** is the midpoint of a data set when the data is arranged in ascending or
descending **order**.
  - **Outliers** occur, the median is a better measure of central tendency than the mean because it is not affected by extreme values
- The mode is the value that occurs most frequently in a data set.
  - distribution has 1 mode: uimodal; bimodal, trimodal
- The mean and variance of a distribution are defined as the first and second moments of the
distribution,
- Variance: Var(X) = E \[(X - u)^2], The square root of the variance is called the standard deviation
  - The variance and standard
deviation provide a measure of the **extent of the dispersion** in the values of the random
variable around the mean.
```
1. Var(X) = E[(X - p)2] = E(X2) - [E(X)]2
where p = E(X)
2. If c is any constant, then:
Var(c) = 0
3. If c is any constant, then:
Var(cX) = c^2 x Var(X)
4. If c is any constant, then:
Var(X + c) = Var(X)
3. If a and c are constants, then:
Var(aX + c) = a^2 x Var(X)
6. If Xand Yare independent random variables, then:
Var(X + Y) = Var(X) + Var(Y)
Var(X - Y) = Var(X) + Var(Y)
7. If Xand Yare independent and a and c are constants, then:
Var(aX + cY) = a^2 x Var(X) + c^2 x Var(Y)
```
2. Calculate the mean, standard deviation, and variance of a discrete random variable,
(page 29)
3. Interpret and calculate the expected value of a discrete random variable, (page 34)
- The expected value is the **weighted average** of the possible outcomes of a random variable,
where the weights are the probabilities that the outcomes will occur.
```
1. If c is any constant, then:
E(cX) = cE(X)
2. If Xand Yare any random variables, then:
E(X + Y) = E(X) + E(Y)
3. If c and a are constants, then:
E(cX + a) = cE(X) + a
4. If X and Y are independent random variables, then:
E(XY) = E(X) x E(Y)
3. If X and Y are NOT independent, then:
E(XY) <> E(X) x E(Y)
6. If X is a random variable, then:
E(X^2) <> [E(X)]^2
```
- [x] 4. Calculate and interpret the covariance and correlation between two random
variables, (page 38)
- Covariance is the expected value of the product of the deviations of the two random
variables from their respective expected values.
  - Cov(Ri,Rj) = E{\[Ri - E(Ri)] \[Rj - E(Rj)]} = E(Ri, Rj) - E(Ri)E(Rj)

- correlation (correlation coefficient): easier to interpret
  - cov divided by the product of the random variables’ standard deviations.
  - p(Ri,Rj)
  - 2 variables
  - [generte correlated random num](https://stats.stackexchange.com/questions/38856/how-to-generate-correlated-random-numbers-given-means-variances-and-degree-of)
  
  
```
• Correlation measures the strength of the linear relationship between two random
variables.
• Correlation has no units.
• The correlation ranges from -1 to +1. That is, —1 < Corr(Rj, R-)< +1.
• If Corr(Rj, Rj) = 1.0, the random variables have perfect positive correlation. This means
that a movement in one random variable results in a proportional positive movement in
the other relative to its mean.
• If Corr(Rj, R.) = —1.0, the random variables have perfect negative correlation. This
means that a movement in one random variable results in an exact opposite proportional
movement in the other relative to its mean.
• If Corr(Rj, R ) = 0, there is no linear relationship between the variables, indicating that
prediction of R cannot be made on the basis of i?- using linear methods.

1. If X and Y are independent random variables, then:
Topic 16
Cross Reference to GARP Assigned Reading - Miller, Chapter 3
Cov(X,Y) = 0
2. The covariance of random variable A with itself is the variance of X.
Cov(X,X) = Var(X)
3. If a, b, c, and d are constants, then:
Cov(a + bX, c + dY) = b x d x Cov(X,Y)
4. IfXand Fare NOT independent, then:
Var(X + Y) = Var(X) + Var(Y) + 2 x Cov(X,Y)
Var(X - Y) = Var(X) + Var(Y) - 2 x Cov(X,Y)
```

- [ ] 5. Calculate the mean and variance of sums of variables, (page 34)

6. Describe the four central moments of a statistical variable or distribution: mean,
variance, skewness and kurtosis. (page 42)
- The shape of a probability distribution can be described by the “moments” of the
distribution. 
- Raw moments are measured relative to an expected value raised to the
appropriate power.
  - Kth raw moment is the expected value of Rk:
  - The first raw moment is the mean of the distribution, which is the expected value of returns
- Central moments are measured relative to the mean (i.e., central around the mean).
  - first central moment: 0
  - The second central moment is the variance of the distribution, which measures the dispersion of data.
  - The third central moment measures the departure from symmetry in the distribution.
    - zero for a **symmetric** distribution (such as the normal distribution).
    - skewness: standardized third central moment, divided by var^3
  - The fourth central moment measures the degree of clustering in the distribution.
    - kurtosis: standardized fourth central moment of the distribution.
    - Kurtosis refers to the degree of **peakedness** or clustering in the data distribution
    - Kurtosis for the normal distribution equals **3**.
    - excess kurtosis = kurtosis — 3
7. Interpret the skewness and kurtosis of a statistical distribution, and interpret the
concepts of coskewness and cokurtosis. (page 44)
- Skewness
  - Positively skewed distribution: many outliers in the upper region, or right tail.
    - long uppper tail
    - mode < median < mean
  - negatively skewed: skew left
    - long lower tail
    - mean < median < mode
- Kurtosis
  - Leptokurtic: more peaked, fat tail
  - Platykurtic: flatter
  - Mesokurtic: normal 
- greater positive kurtosis and more negative skew in returns distributions indicates increased
risk.
- The third
cross central moment is known as coskewness and the fourth cross central moment is
known as cokurtosis.
```
most risk models choose to ignore the effects of coskewness and cokurtosis. The reason being is that
as the number of variables increase, the number of coskewness and cokurtosis terms will
increase rapidly, making the data much more difficult to analyze. Practitioners instead
opt to use more tractable risk models, such as GARCH (see Topic 28), which capture the
essence of coskewness and cokurtosis by incorporating time-varying volatility and/or timevarying
correlation.
```
8. Describe and interpret the best linear unbiased estimator, (page 48)
- Point estimates
are single (sample) values used to estimate population parameters, and the formula used
to compute a point estimate is known as an estimator.
- An **unbiased** estimator is one for which the expected value of the estimator is equal to the
parameter you are trying to estimate.
  - sample mean to population
- An unbiased estimator is also **efficient** if the variance of its sampling distribution is
**smaller** than all the other unbiased estimators of the parameter you are trying to
estimate.
- A **consistent** estimator is one for which the accuracy of the parameter estimate increases as
the sample **size increases**
- A point estimate is a linear estimator when it can be used as a linear function of sample
data.
- best linear unbiased estimator (BLUE): If the estimator is the best available (i.e., has the minimum variance), exhibits linearity, and
is unbiased


### 17. Distributions
- Probability distributions
  - Parametric distributions, such as a normal distribution, can be described by using a
mathematical function.
  - Nonparametric distributions, such as a historical
distribution, cannot be described by using a mathematical function.

After completing this reading, you should be able to:
1. Distinguish the key **properties** among the following distributions: uniform
distribution, Bernoulli distribution, Binomial distribution, Poisson distribution,
normal distribution, lognormal distribution, Chi-squared distribution, Student’s
t, and F-distributions, and identify **common occurrences** of each distribution.
(page 53)
- The continuous uniform distribution is defined over a range that spans between some
lower limit, a, and some upper limit, b, which serve as the parameters of the distribution.
  - P(X < a or X > b) = 0
  - P(x1 < X < x2) = (x2 — x1)/(b — a).
  - probability density function (pdf): f(x) = 1 / (b - a)
  - E(x) = (a + b) / 2
  - Var(x) = (b - a)^2 / 12
- A Bernoulli distributed random variable only has two possible outcomes.
- A binomial random variable may be defined as the number of “successes” in a given
number of trials, whereby the outcome can be either “success” or “failure.”
  - p(x) = P(X = x) = n!/[(n - x)! x!] p^x (1 - p)^(n - x)
  - E(X) = np
  - Var(X) = np(1 - p) = npq
- While the Poisson random variable X refers to the number o f successes p er unit, the parameter
lambda refers to the average or expected number o f successes p er unit.
  - P(X = x) = lbd^x e ^(-lbd) / x!
- normal distribution
  - X is normally distributed with mean u and variance v2
  - Skewness = 0
  - Kurtosis = 3
  - A linear combination of normally distributed independent random variables is also normally distributed.
  - A confidence interval is a range of values around the expected outcome within which we expect the actual outcome to be some specified percentage of the time.
    - The 90% confidence interval for X is X - 1.65s to X + 1.65s.
    - The 95% confidence interval for X is X - 1.96s to X + 1.96s.
    - The 99% confidence interval for X is X — 2.58s to X + 2.58s.
- A standard normal distribution (i.e., ^-distribution) is a normal distribution that has been
standardized so it has a mean of zero and a standard deviation of 1 [i.e., N~(0,1)].
  - z = (observation — population mean) / standard deviation
  
2. Describe the **central limit** theorem and the implications it has when combining
independent and identically distributed (i.i.d.) random variables, (page 66)
3. Describe i.i.d. random variables and the implications of the i.i.d. assumption when
combining random variables, (page 66)
- If the sample size n is sufficiently large (n > 30), the sampling distribution of the sample means will be approximately normal. Remember what’s going on here: random samples of size n are repeatedly being taken from an overall larger population. Each of these random samples has its own mean, which is itself a random variable, and this set of sample means has a distribution that is approximately normal.
- The mean of the population, p, and the mean of the distribution of all possible sample means are equal.
- The variance of the distribution of sample means is — , the population variance divided by the sample size.

4. Describe a mixture distribution and explain the creation and characteristics of
mixture distributions, (page 70)

### 18. Bayesian Analysis
After completing this reading, you should be able to:
1. Describe Bayes’ theorem and apply this theorem in the calculation of conditional
probabilities, (page 75)
2. Compare the Bayesian approach to the frequentist approach, (page 80)
3. Apply Bayes’ theorem to scenarios with more than two possible outcomes and
calculate posterior probabilities, (page 81)

### 19. Hypothesis Testing and Confidence Intervals
After completing this reading, you should be able to:
1. Calculate and interpret the sample mean and sample variance, (page 90)
2. Construct and interpret a confidence interval, (page 96)
3. Construct an appropriate null and alternative hypothesis, and calculate an
appropriate test statistic, (page 100)
4. Differentiate between a one-tailed and a two-tailed test and identify when to use
each test, (page 102)
5. Interpret the results of hypothesis tests with a specific level of confidence.
(page 113)
6. Demonstrate the process of backtesting VaR by calculating the number of
exceedances, (page 121)



### 20. Linear Regression with One Regressor
After completing this reading, you should be able to:
1. Explain how regression analysis in econometrics measures the relationship between
dependent and independent variables, (page 128)
2. Interpret a population regression function, regression coefficients, parameters, slope,
intercept, and the error term, (page 129)
3. Interpret a sample regression function, regression coefficients, parameters, slope,
intercept, and the error term, (page 130)
4. Describe the key properties of a linear regression, (page 131)
3. Define an ordinary least squares (OLS) regression and calculate the intercept and
slope of the regression, (page 132)
6. Describe the method and three key assumptions of OLS for estimation of
parameters, (page 133)
7. Summarize the benefits of using OLS estimators, (page 133)
8. Describe the properties of OLS estimators and their sampling distributions, and
explain the properties of consistent estimators in general, (page 133)
9. Interpret the explained sum of squares, the total sum of squares, the residual sum of
squares, the standard error of the regression, and the regression R2. (page 134)
10. Interpret the results of an OLS regression, (page 134)

### 21. Regression with a Single Regressor: Hypothesis Tests and Confidence Intervals
After completing this reading, you should be able to:
1. Calculate and interpret confidence intervals for regression coefficients, (page 142)
2. Interpret the p-value. (page 144)
3. Interpret hypothesis tests about regression coefficients, (page 143)
4. Evaluate the implications of homoskedasticity and heteroskedasticity. (page 147)
5. Determine the conditions under which the OLS is the best linear conditionally
unbiased estimator, (page 149)
6. Explain the Gauss-Markov Theorem and its limitations, and alternatives to the
OLS. (page 149)
7. Apply and interpret the t-statistic when the sample size is small, (page 150)

### 22. Linear Regression with Multiple Regressors
After completing this reading, you should be able to:
1. Define and interpret omitted variable bias, and describe the methods for addressing
this bias, (page 156)
2. Distinguish between single and multiple regression, (page 157)
3. Interpret the slope coefficient in a multiple regression, (page 158)
4. Describe homoskedasticity and heteroskedasticity in a multiple regression.
(page 159)
5. Describe the OLS estimator in a multiple regression, (page 157)
6. Calculate and interpret measures of fit in multiple regression, (page 159)
7. Explain the assumptions of the multiple linear regression model, (page 162)
8. Explain the concepts of imperfect and perfect multicollinearity and their
implications, (page 162)
### 23. Hypothesis Tests and Confidence Intervals in Multiple Regression
After completing this reading, you should be able to:
1. Construct, apply, and interpret hypothesis tests and confidence intervals for a single
coefficient in a multiple regression, (page 170)
2. Construct, apply, and interpret joint hypothesis tests and confidence intervals for
multiple coefficients in a multiple regression, (page 176)
3. Interpret the F-statistic. (page 176)
4. Interpret tests of a single restriction involving multiple coefficients, (page 182)
5. Interpret confidence sets for multiple coefficients, (page 176)
6. Identify examples of omitted variable bias in multiple regressions, (page 183)
7. Interpret the R2 and adjusted R2 in a multiple regression, (page 181)
### 24. Modeling and Forecasting Trend
After completing this reading, you should be able to:
1. Describe linear and nonlinear trends, (page 189)
2. Describe trend models to estimate and forecast trends, (page 192)
3. Compare and evaluate model selection criteria, including mean squared error
(MSE), s2, the Akaike information criterion (AIC), and the Schwarz information
criterion (SIC), (page 197)
4. Explain the necessary conditions for a model selection criterion to demonstrate
consistency, (page 200)

### 25. Modeling and Forecasting Seasonality
After completing this reading, you should be able to:
1. Describe the sources of seasonality and how to deal with it in time series analysis,
(page 206)
2. Explain how to use regression analysis to model seasonality, (page 208)
3. Explain how to construct an h-step-ahead point forecast, (page 210)
### 26. Characterizing Cycles
After completing this reading, you should be able to:
1. Define covariance stationary, autocovariance function, autocorrelation function,
partial autocorrelation function, and autoregression, (page 214)
2. Describe the requirements for a series to be covariance stationary, (page 214)
3. Explain the implications of working with models that are not covariance stationary,
(page 217)

4. Define white noise, and describe independent white noise and normal (Gaussian)
white noise, (page 218)
5. Explain the characteristics of the dynamic structure of white noise, (page 218)
6. Explain how a lag operator works, (page 220)
7. Describe Wold’s theorem, (page 221)
8. Define a general linear process, (page 221)
9. Relate rational distributed lags to Wold’s theorem, (page 221)
10. Calculate the sample mean and sample autocorrelation, and describe the Box-Pierce
Q-statistic and the Ljung-Box Q-statistic. (page 221)
11. Describe sample partial autocorrelation, (page 221)
### 27. Modeling Cycles: MA, AR, and ARMA Models
After completing this reading, you should be able to:
1. Describe the properties of the first-order moving average (MA(1)) process,
and distinguish between autoregressive representation and moving average
representation, (page 229)
2. Describe the properties of a general finite-order process of order q (MA(q)) process,
(page 231)
3. Describe the properties of the first-order autoregressive (AR(1)) process, and define
and explain the Yule-Walker equation, (page 231)
4. Describe the properties of a general p th order autoregressive (AR(p)) process.
(page 233)
5. Define and describe the properties of the autoregressive moving average (ARMA)
process, (page 233)
6. Describe the application of AR and ARMA processes, (page 234)
### 28. Volatility
After completing this reading, you should be able to:
1. Define and distinguish between volatility, variance rate, and implied volatility.
(page 239)
2. Describe the power law. (page 240)
3. Explain how various weighting schemes can be used in estimating volatility.
(page 242)
4. Apply the exponentially weighted moving average (EWMA) model to estimate
volatility, (page 243)
3. Describe the generalized autoregressive conditional heteroskedasticity (GARCH
(p,q)) model for estimating volatility and its properties, (page 244)
6. Calculate volatility using the GARCH(1,1) model, (page 244)
7. Explain mean reversion and how it is captured in the GARCH(1,1) model.
(page 245)
8. Explain the weights in the EWMA and GARCH(1,1) models, (page 243)
9. Explain how GARCH models perform in volatility forecasting, (page 246)
10. Describe the volatility term structure and the impact of volatility changes.
(page 246)
### 29. Correlations and Copulas
After completing this reading, you should be able to:
1. Define correlation and covariance and differentiate between correlation and
dependence, (page 251)
2. Calculate covariance using the EWMA and GARCH(1,1) models, (page 253)
3. Apply the consistency condition to covariance, (page 236)
4. Describe the procedure of generating samples from a bivariate normal distribution,
(page 257)
5. Describe properties of correlations between normally distributed variables when
using a one-factor model, (page 258)
6. Define copula and describe the key properties of copulas and copula correlation,
(page 258)
8. Describe the Gaussian copula, Student’s t-copula, multivariate copula, and onefactor
copula, (page 260)
7. Explain tail dependence, (page 262)
### 30. Simulation Methods
After completing this reading, you should be able to:
1. Describe the basic steps to conduct a Monte Carlo simulation, (page 269)
2. Describe ways to reduce Monte Carlo sampling error, (page 270)
3. Explain how to use antithetic variate technique to reduce Monte Carlo sampling
error, (page 271)
4. Explain how to use control variates to reduce Monte Carlo sampling error and
when it is effective, (page 272)
5. Describe the benefits of reusing sets of random number draws across Monte Carlo
experiments and how to reuse them, (page 273)
6. Describe the bootstrapping method and its advantage over Monte Carlo simulation,
(page 274)
8. Describe situations where the bootstrapping method is ineffective, (page 275)
7. Describe the pseudo-random number generation method and how a good
simulation design alleviates the effects the choice of the seed has on the properties
of the generated series, (page 275)
9. Describe disadvantages of the simulation approach to financial problem solving,
(page 276)

## Financial Markets and Products

### 31. Banks
1. Identify the major risks faced by a bank, (page 1)
2. Distinguish between economic capital and regulatory capital, (page 2)
3. Explain how deposit insurance gives rise to a moral hazard problem, (page 2)
4. Describe investment banking financing arrangements including private placement,
public offering, best efforts, firm commitment, and Dutch auction approaches,
(page 3)
3. Describe the potential conflicts of interest among commercial banking, securities
services, and investment banking divisions of a bank and recommend solutions to
the conflict of interest problems, (page 4)
6. Describe the distinctions between the “banking book” and the “trading book” of a
bank, (page 4)
7. Explain the originate-to-distribute model of a bank and discuss its benefits and
drawbacks, (page 5)
### 32. Insurance Companies and Pension Plans
1. Describe the key features of the various categories of insurance companies and
identify the risks facing insurance companies, (page 10)
2. Describe the use of mortality tables and calculate the premium payment for a policy
holder, (page 12)
3. Calculate and interpret loss ratio, expense ratio, combined ratio, and operating ratio
for a property-casualty insurance company, (page 15)
4. Describe moral hazard and adverse selection risks facing insurance companies,
provide examples of each, and describe how to overcome the problems, (page 15)
5. Distinguish between mortality risk and longevity risk and describe how to hedge
these risks, (page 16)
6. Evaluate the capital requirements for life insurance and property-casualty insurance
companies, (page 16)
7. Compare the guaranty system and the regulatory requirements for insurance
companies with those for banks, (page 17)
8. Describe a defined benefit plan and a defined contribution plan for a pension fund
and explain the differences between them, (page 18)
### 33. Mutual Funds and Hedge Funds
1. Differentiate among open-end mutual funds, closed-end mutual funds, and
exchange-traded funds (ETFs). (page 24)
2. Calculate the net asset value (NAV) of an open-end mutual fund, (page 28)
3. Explain the key differences between hedge funds and mutual funds, (page 28)
4. Calculate the return on a hedge fund investment and explain the incentive fee
structure of a hedge fund including the terms hurdle rate, high-water mark, and
clawback, (page 29)
5. Describe various hedge fund strategies, including long/short equity, dedicated short,
distressed securities, merger arbitrage, convertible arbitrage, fixed income arbitrage,
emerging markets, global macro, and managed futures, and identify the risks faced
by hedge funds, (page 31)
6. Describe hedge fund performance and explain the effect of measurement biases on
performance measurement, (page 34)

### 34. Introduction (Options, Futures, and Other Derivatives)
1. Describe the over-the-counter market, distinguish it from trading on an exchange,
and evaluate its advantages and disadvantages, (page 41)
2. Differentiate between options, forwards, and futures contracts, (page 42)
3. Identify and calculate option and forward contract payoffs, (page 42)
4. Calculate and compare the payoffs from hedging strategies involving forward
contracts and options, (page 47)
5. Calculate and compare the payoffs from speculative strategies involving futures and
options, (page 48)
6. Calculate an arbitrage payoff and describe how arbitrage opportunities are
temporary, (page 31)
7. Describe some o f the risks that can arise from the use o f derivatives, (page 51)
8. Differentiate among the broad categories of traders: hedgers, speculators, and
arbitrageurs, (page 46)
### 35. Futures Markets and Central Counterparties
1. Define and describe the key features o f a futures contract, including the asset, the
contract price and size, delivery, and limits, (page 56)
2. Explain the convergence of futures and spot prices, (page 58)
3. Describe the rationale for margin requirements and explain how they work.
(page 58)
4. Describe the role of a clearinghouse in futures and over-the-counter market
transactions, (page 59)
5. Describe the role o f central counterparties (CCPs) and distinguish between bilateral
and centralized clearing, (page 60)
6. Describe the role o f collateralization in the over-the-counter market and compare it
to the margining system, (page 60)
7. Identify the differences between a normal and inverted futures market, (page 62)
8. Explain the different market quotes, (page 62)
9. Describe the mechanics o f the delivery process and contrast it with cash settlement,
(page 63)
10. Evaluate the impact of different trading order types, (page 64)
11. Compare and contrast forward and futures contracts, (page 64)
### 36. Hedging Strategies Using Futures
1. Define and differentiate between short and long hedges and identify their
appropriate uses, (page 70)
2. Describe the arguments for and against hedging and the potential impact of
hedging on firm profitability, (page 70)
3. Define the basis and explain the various sources o f basis risk, and explain how basis
risks arise when hedging with futures, (page 71)
4. Define cross hedging, and compute and interpret the minimum variance hedge
ratio and hedge effectiveness, (page 71)
5. Compute the optimal number of futures contracts needed to hedge an exposure,
and explain and calculate the “tailing the hedge” adjustment, (page 74)
6. Explain how to use stock index futures contracts to change a stock portfolio’s beta.
(page 75)
7. Explain the term “rolling the hedge forward” and describe some o f the risks that
arise from this strategy, (page 76)
### 37. Interest Rates
1. Describe Treasury rates, LIBOR, and repo rates, and explain what is meant by the
“risk-free” rate, (page 82)
2. Calculate the value of an investment using different compounding frequencies.
(page 83)
3. Convert interest rates based on different compounding frequencies, (page 83)
4. Calculate the theoretical price of a bond using spot rates, (page 84)
5. Derive forward interest rates from a set of spot rates, (page 88)
6. Derive the value of the cash flows from a forward rate agreement (FRA), (page 89)
7. Calculate the duration, modified duration, and dollar duration of a bond, (page 90)
8. Evaluate the limitations of duration, and explain how convexity addresses some of
them, (page 91)
9. Calculate the change in a bond’s price given its duration, its convexity, and a change
in interest rates, (page 92)
10. Compare and contrast the major theories o f the term structure of interest rates,
(page 93)
### 38. Determination of Forward and Futures Prices
1. Differentiate between investment and consumption assets, (page 98)
2. Define short-selling and calculate the net profit o f a short sale of a dividend-paying
stock, (page 98)
3. Describe the differences between forward and futures contracts and explain the
relationship between forward and spot prices, (page 99)
4. Calculate the forward price given the underlying asset’s spot price, and describe an
arbitrage argument between spot and forward prices, (page 99)
3. Explain the relationship between forward and futures prices, (page 103)
6. Calculate a forward foreign exchange rate using the interest rate parity relationship,
(page 102)
7. Define income, storage costs, and convenience yield, (page 104)
8. Calculate the futures price on commodities incorporating income/storage costs and/
or convenience yields, (page 104)
9. Calculate, using the cost-of-carry model, forward prices where the underlying asset
either does or does not have interim cash flows, (page 99)
10. Describe the various delivery options available in the futures markets and how they
can influence futures prices, (page 105)
11. Explain the relationship between current futures prices and expected future spot
prices, including the impact of systematic and nonsystematic risk, (page 105)
12. Define and interpret contango and backwardation, and explain how they relate to
the cost-of-carry model, (page 106)
### 39. Interest Rate Futures
1. Identify the most commonly used day count conventions, describe the markets that
each one is typically used in, and apply each to an interest calculation, (page 111)
2. Calculate the conversion of a discount rate to a price for a US Treasury bill.
(page 113)
3. Differentiate between the clean and dirty price for a US Treasury bond; calculate
the accrued interest and dirty price on a US Treasury bond, (page 112)
4. Explain and calculate a US Treasury bond futures contract conversion factor.
(page 114)
5.Calculate the cost o f delivering a bond into a Treasury bond futures contract,
(page 114)
6.Describe the impact of the level and shape of the yield curve on the cheapest-todeliver
Treasury bond decision, (page 114)
7.Calculate the theoretical futures price for a Treasury bond futures contract.
(page 115)
8.Calculate the final contract price on a Eurodollar futures contract, (page 117)
Describe and compute the Eurodollar futures contract convexity adjustment,
(page 117)
9.Explain how Eurodollar futures can be used to extend the LIBOR zero curve,
(page 118)
10.Calculate the duration-based hedge ratio and create a duration-based hedging
strategy using interest rate futures, (page 118)
11.Explain the limitations of using a duration-based hedging strategy, (page 119)
12.
### 40. Swaps
1. Explain the mechanics o f a plain vanilla interest rate swap and compute its cash
flows, (page 123)
2. Explain how a plain vanilla interest rate swap can be used to transform an asset or a
liability and calculate the resulting cash flows, (page 126)
3. Explain the role of financial intermediaries in the swaps market, (page 126)
4. Describe the role of the confirmation in a swap transaction, (page 126)
5. Describe the comparative advantage argument for the existence of interest rate
swaps and evaluate some o f the criticisms of this argument, (page 127)
6. Explain how the discount rates in a plain vanilla interest rate swap are computed,
(page 128)
7. Calculate the value of a plain vanilla interest rate swap based on two simultaneous
bond positions, (page 128)
8. Calculate the value of a plain vanilla interest rate swap from a sequence of forward
rate agreements (FRAs). (page 130)
9. Explain the mechanics o f a currency swap and compute its cash flows, (page 132)
10. Explain how a currency swap can be used to transform an asset or liability and
calculate the resulting cash flows, (page 134)
11. Calculate the value of a currency swap based on two simultaneous bond positions,
(page 132)
12. Calculate the value of a currency swap based on a sequence of FRAs. (page 133)
13. Describe the credit risk exposure in a swap position, (page 135)
14. Identify and describe other types of swaps, including commodity, volatility and
exotic swaps, (page 135)
### 41. Mechanics of Options Markets
1. Describe the types, position variations, and typical underlying assets of options,
(page 142)
2. Explain the specification o f exchange-traded stock option contracts, including that
of nonstandard products, (page 148)
3. Describe how trading, commissions, margin requirements, and exercise typically
work for exchange-traded options, (page 150)
### 42. Properties of Stock Options
1. Identify the six factors that affect an option’s price and describe how these six
factors affect the price for both European and American options, (page 157)
2. Identify and compute upper and lower bounds for option prices on non-dividend
and dividend paying stocks, (page 159)
3. Explain put-call parity and apply it to the valuation of European and American
stock options, (page 160)
4. Explain the early exercise features of American call and put options, (page 162)
### 43. Trading Strategies Involving Options
1. Explain the motivation to initiate a covered call or a protective put strategy.
(page 169)
2. Describe the use and calculate the payoffs of various spread strategies, (page 170)
3. Describe the use and explain the payoff functions o f combination strategies.
(page 175)
### 44. Exotic Options
1. Define and contrast exotic derivatives and plain vanilla derivatives, (page 185)
2. Describe some of the factors that drive the development of exotic products.
(page 185)
3. Explain how any derivative can be converted into a zero-cost product, (page 186)
4. Describe how standard American options can be transformed into nonstandard
American options, (page 186)
5. Identify and describe the characteristics and pay-off structure o f the following exotic
options: gap, forward start, compound, chooser, barrier, binary, lookback, shout,
Asian, exchange, rainbow, and basket options, (page 187)
6. Describe and contrast volatility and variance swaps, (page 190)
7. Explain the basic premise of static option replication and how it can be applied to
hedging exotic options, (page 191)
### 45. Commodity Forwards and Futures
1. Apply commodity concepts such as storage costs, carry markets, lease rate, and
convenience yield, (page 196)
2. Explain the basic equilibrium formula for pricing commodity forwards, (page 197)
3. Describe an arbitrage transaction in commodity forwards, and compute the
potential arbitrage profit, (page 198)
4. Define the lease rate and explain how it determines the no-arbitrage values for
commodity forwards and futures, (page 201)
5. Define carry markets, and illustrate the impact of storage costs and convenience
yields on commodity forward prices and no-arbitrage bounds, (page 204)
6. Compute the forward price of a commodity with storage costs, (page 204)
7. Compare the lease rate with the convenience yield, (page 206)
8. Identify factors that impact gold, corn, electricity, natural gas, and oil forward
prices, (page 207)
9. Compute a commodity spread, (page 209)
10. Explain how basis risk can occur when hedging commodity price exposure.
(page 210)
11. Evaluate the differences between a strip hedge and a stack hedge and explain how
these differences impact risk management, (page 211)
12. Provide examples o f cross-hedging, specifically the process o f hedging jet fuel with
crude oil and using weather derivatives, (page 212)
13. Explain how to create a synthetic commodity position, and use it to explain
the relationship between the forward price and the expected future spot price.
(page 197)
46. Exchanges, OTC Derivatives, DPCs and SPVs
1. Describe how exchanges can be used to alleviate counterparty risk, (page 219)
2. Explain the developments in clearing that reduce risk, (page 219)
3. Compare exchange-traded and OTC markets and describe their uses, (page 220)
4. Identify the classes of derivative securities and explain the risk associated with them,
(page 221)
5. Identify risks associated with OTC markets and explain how these risks can be
mitigated, (page 222)
### 47. Basic Principles of Central Clearing
1. Provide examples of the mechanics of a central counterparty (CCP). (page 229)
2. Describe advantages and disadvantages of central clearing of OTC derivatives.
(page 231)
3. Compare margin requirements in centrally cleared and bilateral markets, and
explain how margin can mitigate risk, (page 233)
4. Compare and contrast bilateral markets to the use of novation and netting.
(page 233)
3. Assess the impact o f central clearing on the broader financial markets, (page 234)
### 48. Risks Caused by CCPs
1. Identify and explain the types of risks faced by CCPs. (page 240)
2. Identify and distinguish between the risks to clearing members as well as nonmembers.
(page 242)
3. Identify and evaluate lessons learned from prior CCP failures, (page 243)
### 49. Foreign Exchange Risk
1. Calculate a financial institution’s overall foreign exchange exposure, (page 247)
2. Explain how a financial institution could alter its net position exposure to reduce
foreign exchange risk, (page 248)
3. Calculate a financial institution’s potential dollar gain or loss exposure to a
particular currency, (page 248)
4. Identify and describe the different types of foreign exchange trading activities.
(page 249)
5. Identify the sources of foreign exchange trading gains and losses, (page 249)
6. Calculate the potential gain or loss from a foreign currency denominated
investment, (page 250)
7. Explain balance-sheet hedging with forwards, (page 252)
8. Describe how a non-arbitrage assumption in the foreign exchange markets leads to
the interest rate parity theorem, and use this theorem to calculate forward foreign
exchange rates, (page 255)
9. Explain why diversification in multicurrency asset-liability positions could reduce
portfolio risk, (page 256)
10. Describe the relationship between nominal and real interest rates, (page 256)
### 50. Corporate Bonds
1. Describe a bond indenture and explain the role of the corporate trustee in a bond
indenture, (page 262)
2. Explain a bond’s maturity date and how it impacts bond retirements, (page 262)
3. Describe the main types of interest payment classifications, (page 263)
4. Describe zero-coupon bonds and explain the relationship between original-issue
discount and reinvestment risk, (page 263)
5. Distinguish among the following security types relevant for corporate bonds:
mortgage bonds, collateral trust bonds, equipment trust certificates, subordinated
and convertible debenture bonds, and guaranteed bonds, (page 264)
6. Describe the mechanisms by which corporate bonds can be retired before maturity,
(page 266)
7. Differentiate between credit default risk and credit spread risk, (page 267)
8. Describe event risk and explain what may cause it in corporate bonds, (page 268)
9. Define high-yield bonds, and describe types of high-yield bond issuers and some of
the payment features unique to high yield bonds, (page 268)
10. Define and differentiate between an issuer default rate and a dollar default rate,
(page 269)
11. Define recovery rates and describe the relationship between recovery rates and
seniority, (page 270)
### 51. Mortgages and Mortgage-Backed Securities
1. Describe the various types of residential mortgage products, (page 275)
2. Calculate a fixed rate mortgage payment, and its principal and interest components,
(page 278)
3. Describe the mortgage prepayment option and the factors that influence
prepayments, (page 281)
4. Summarize the securitization process of mortgage backed securities (MBS),
particularly formation of mortgage pools including specific pools and TBAs.
(page 282)
5. Calculate weighted average coupon, weighted average maturity, and conditional
prepayment rate (CPR) for a mortgage pool, (page 282)
6. Describe a dollar roll transaction and how to value a dollar roll, (page 287)
7. Explain prepayment modeling and its four components: refinancing, turnover,
defaults, and curtailments, (page 290)
8. Describe the steps in valuing an MBS using Monte Carlo simulation, (page 292)
9. Define Option Adjusted Spread (OAS), and explain its challenges and its uses.
(page 295)
## Valuation and Risk Models
### 52. Quantifying Volatility in VaR Models
After completing this reading, you should be able to:
1. Explain how asset return distributions tend to deviate from the normal distribution,
(page 12)
2. Explain reasons for fat tails in a return distribution and describe their implications,
(page 12)
3. Distinguish between conditional and unconditional distributions, (page 12)
4. Describe the implications of regime switching on quantifying volatility, (page 14)
5. Explain the various approaches for estimating VaR. (page 15)
6. Compare and contrast different parametric and non-parametric approaches for
estimating conditional volatility, (page 15)
7. Calculate conditional volatility using parametric and non-parametric approaches,
(page 15)
8. Explain the process of return aggregation in the context of volatility forecasting
methods, (page 25)
9. Evaluate implied volatility as a predictor of future volatility and its shortcomings,
(page 25)
10. Explain long horizon volatility/VaR and the process of mean reversion according to
an AR(1) model, (page 26)
11. Calculate conditional volatility with and without mean reversion, (page 26)
12. Describe the impact of mean reversion on long horizon conditional volatility
estimation, (page 26)
### 53. Putting VaR to Work
After completing this reading, you should be able to:
1. Explain and give examples of linear and non-linear derivatives, (page 34)
2. Describe and calculate VaR for linear derivatives, (page 36)
3. Describe the delta-normal approach for calculating VaR for non-linear derivatives,
(page 36)
4. Describe the limitations of the delta-normal method, (page 36)
5. Explain the full revaluation method for computing VaR. (page 40)
6. Compare delta-normal and full revaluation approaches for computing VaR.
(page 40)
7. Explain structured Monte Carlo, stress testing, and scenario analysis methods for
computing VaR, and identify strengths and weaknesses of each approach, (page 40)
8. Describe the implications of correlation breakdown for scenario analysis, (page 40)
9. Describe Worst-Case Scenario (WCS) analysis and compare WCS to VaR. (page 42)
### 54. Measures of Financial Risk
After completing this reading, you should be able to:
1. Describe the mean-variance framework and the efficient frontier, (page 48)
2. Explain the limitations of the mean-variance framework with respect to
assumptions about the return distributions, (page 50)
3. Define the VaR measure of risk, describe assumptions about return distributions
and holding period, and explain the limitations of VaR (page 51)
4. Define the properties of a coherent risk measure and explain the meaning of each
property, (page 52)
5. Explain why VaR is not a coherent risk measure, (page 53)

6. Explain and calculate Expected Shortfall (ES), and compare and contrast VaR and
ES. (page 53)
7. Describe spectral risk measures, and explain how VaR and ES are special cases of
spectral risk measures, (page 54)
8. Describe how the results of scenario analysis can be interpreted as coherent risk
measures, (page 54)
### 55. Binomial Trees
After completing this reading, you should be able to:
1. Calculate the value of an American and a European call or put option using a onestep
and two-step binomial model, (page 60)
2. Describe how volatility is captured in the binomial model, (page 67)
3. Describe how the value calculated using a binomial model converges as time periods
are added, (page 70)
4. Explain how the binomial model can be altered to price options on: stocks with
dividends, stock indices, currencies, and futures, (page 67)
5. Define and calculate delta of a stock option, (page 62)
### 56. The Black-Scholes-Merton Model
After completing this reading, you should be able to:
1. Explain the lognormal property of stock prices, the distribution of rates of return,
and the calculation of expected return, (page 77)
2. Compute the realized return and historical volatility of a stock, (page 77)
3. Describe the assumptions underlying the Black-Scholes-Merton option pricing
model, (page 80)
4. Compute the value of a European option using the Black-Scholes-Merton model on
a non-dividend-paying stock, (page 81)
5. Compute the value of a warrant and identify the complications involving the
valuation of warrants, (page 87)
6. Define implied volatilities and describe how to compute implied volatilities from
market prices of options using the Black-Scholes-Merton model, (page 88)
7. Explain how dividends affect the decision to exercise early for American call and
put options, (page 86)
8. Compute the value of a European option using the Black-Scholes-Merton model on
a dividend-paying stock, (page 83)
### 57. The Greek Letters
After completing this reading, you should be able to:
1. Describe and assess the risks associated with naked and covered option positions,
(page 95)
2. Explain how naked and covered option positions generate a stop loss trading
strategy, (page 96)
3. Describe delta hedging for an option, forward, and futures contracts, (page 96)
4. Compute the delta of an option, (page 96)
5. Describe the dynamic aspects of delta hedging and distinguish between dynamic
hedging and hedge-and-forget strategy, (page 99)
6. Define the delta of a portfolio, (page 102)
7. Define and describe theta, gamma, vega, and rho for option positions, (page 103)
8. Explain how to implement and maintain a delta-neutral and a gamma-neutral
position, (page 103)
9. Describe the relationship between delta, theta, gamma, and vega, (page 103)
10. Describe how hedging activities take place in practice, and describe how scenario
analysis can be used to formulate expected gains and losses with option positions.
(page 109)
11. Describe how portfolio insurance can be created through option instruments and
stock index futures, (page 110)
### 58. Prices, Discount Factors, and Arbitrage
After completing this reading, you should be able to:
1. Define discount factor and use a discount function to compute present and future
values, (page 118)
2. Define the “law of one price,” explain it using an arbitrage argument, and describe
how it can be applied to bond pricing, (page 120)
3. Identify the components of a US Treasury coupon bond, and compare and contrast
the structure to Treasury STRIPS, including the difference between P-STRIPS and
C-STRIPS. (page 122)
4. Construct a replicating portfolio using multiple fixed income securities to match
the cash flows of a given fixed income security, (page 123)
5. Identify arbitrage opportunities for fixed income securities with certain cash flows.
(page 120)
6. Differentiate between “clean” and “dirty” bond pricing and explain the implications
of accrued interest with respect to bond pricing, (page 124)
7. Describe the common day-count conventions used in bond pricing, (page 124)
### 59. Spot, Forward, and Par Rates
After completing this reading, you should be able to:
1. Calculate and interpret the impact of different compounding frequencies on a
bond’s value, (page 131)
2. Calculate discount factors given interest rate swap rates, (page 132)
3. Compute spot rates given discount factors, (page 134)
4. Interpret the forward rate, and compute forward rates given spot rates, (page 136)
5. Define par rate and describe the equation for the par rate of a bond, (page 138)
6. Interpret the relationship between spot, forward, and par rates, (page 139)
7. Assess the impact of maturity on the price of a bond and the returns generated by
bonds, (page 141)
8. Define the “flattening” and “steepening” of rate curves and describe a trade to
reflect expectations that a curve will flatten or steepen, (page 141)
### 60. Returns, Spreads, and Yields
After completing this reading, you should be able to:
1. Distinguish between gross and net realized returns, and calculate the realized return
for a bond over a holding period including reinvestments, (page 149)
2. Define and interpret the spread of a bond, and explain how a spread is derived from
a bond price and a term structure of rates, (page 151)
3. Define, interpret, and apply a bond’s yield-to-maturity (YTM) to bond pricing.
(page 151)
4. Compute a bond’s YTM given a bond structure and price, (page 151)
5. Calculate the price of an annuity and a perpetuity, (page 155)
6. Explain the relationship between spot rates and YTM. (page 156)
7. Define the coupon effect and explain the relationship between coupon rate, YTM,
and bond prices, (page 157)
8. Explain the decomposition of P&L for a bond into separate factors including carry
roll-down, rate change, and spread change effects, (page 158)
9. Identify the most common assumptions in carry roll-down scenarios, including
realized forwards, unchanged term structure, and unchanged yields, (page 159)
### 61. One-Factor Risk Metrics and Hedges
After completing this reading, you should be able to:
1. Describe an interest rate factor and identify common examples of interest rate
factors, (page 165)
2. Define and compute the DV01 of a fixed income security given a change in yield
and the resulting change in price, (page 166)
3. Calculate the face amount of bonds required to hedge an option position given the
DV01 of each, (page 166)
4. Define, compute, and interpret the effective duration of a fixed income security
given a change in yield and the resulting change in price, (page 168)
5. Compare and contrast DV01 and effective duration as measures of price sensitivity,
(page 170)
6. Define, compute, and interpret the convexity of a fixed income security given a
change in yield and the resulting change in price, (page 171)
7. Explain the process of calculating the effective duration and convexity of a portfolio
of fixed income securities, (page 173)
8. Explain the impact of negative convexity on the hedging of fixed income securities,
(page 174)
9. Construct a barbell portfolio to match the cost and duration of a given bullet
investment, and explain the advantages and disadvantages of bullet versus barbell
portfolios, (page 175)
### 62. Multi-Factor Risk Metrics and Hedges
After completing this reading, you should be able to:
1. Describe and assess the major weakness attributable to single-factor approaches
when hedging portfolios or implementing asset liability techniques, (page 182)
2. Define key rate exposures and know the characteristics of key rate exposure factors
including partial ‘01s and forward-bucket ‘01s. (page 183)
3. Describe key-rate shift analysis, (page 183)
4. Define, calculate, and interpret key rate ‘01 and key rate duration, (page 184)
5. Describe the key rate exposure technique in multi-factor hedging applications;
summarize its advantages and disadvantages, (page 185)
6. Calculate the key rate exposures for a given security, and compute the appropriate
hedging positions given a specific key rate exposure profile, (page 185)
7. Relate key rates, partial ‘01s and forward-bucket ‘01s, and calculate the forward
bucket ‘01 for a shift in rates in one or more buckets, (page 187)
8. Construct an appropriate hedge for a position across its entire range of forwardbucket
exposures, (page 188)
9. Apply key rate and multi-factor analysis to estimating portfolio volatility.
(page 189)
### 63. Country Risk: Determinants, Measures and Implications
After completing this reading, you should be able to:
1. Identify sources of country risk (page 195)
2. Explain how a country’s position in the economic growth life cycle, political risk,
legal risk, and economic structure affect its risk exposure, (page 196)
3. Evaluate composite measures of risk that incorporate all types of country risk and
explain limitations of the risk services, (page 198)
4. Compare instances of sovereign default in both foreign currency debt and local
currency debt, and explain common causes of sovereign defaults, (page 198)
5. Describe the consequences of sovereign default, (page 200)
6. Describe factors that influence the level of sovereign default risk; explain and assess
how rating agencies measure sovereign default risks, (page 201)
7. Describe the advantages and disadvantages of using the sovereign default spread as a
predictor of defaults, (page 206)
### 64. External and Internal Ratings
After completing this reading, you should be able to:
1. Describe external rating scales, the rating process, and the link between ratings and
default, (page 214)
2. Describe the impact of time horizon, economic cycle, industry, and geography on
external ratings, (page 216)
3. Explain the potential impact of ratings changes on bond and stock prices.
(page 217)
4. Compare external and internal ratings approaches, (page 217)
5. Explain and compare the through-the-cycle and at-the-point internal ratings
approaches, (page 218)
6. Describe a ratings transition matrix and explain its uses, (page 215)
7. Describe the process for and issues with building, calibrating, and backtesting an
internal rating system, (page 218)
8. Identify and describe the biases that may affect a rating system, (page 219)
### 65. Capital Structure in Banks
After completing this reading, you should be able to:
1. Evaluate a bank’s economic capital relative to its level of credit risk, (page 230)
2. Identify and describe important factors used to calculate economic capital for credit
risk: probability of default, exposure, and loss rate, (page 224)
3. Define and calculate expected loss (EL), (page 225)
4. Define and calculate unexpected loss (UL). (page 225)
5. Estimate the variance of default probability assuming a binomial distribution.
(page 225)
6. Calculate UL for a portfolio and the risk contribution of each asset, (page 227)
7. Describe how economic capital is derived, (page 230)
8. Explain how the credit loss distribution is modeled, (page 231)
9. Describe challenges to quantifying credit risk, (page 231)
### 66. Operational Risk
After completing this reading, you should be able to:
1. Compare three approaches for calculating regulatory capital, (page 237)
2. Describe the Basel Committee’s seven categories of operational risk, (page 238)
3. Derive a loss distribution from the loss frequency distribution and loss severity
distribution using Monte Carlo simulations, (page 239)
4. Describe the common data issues that can introduce inaccuracies and biases in the
estimation of loss frequency and severity distributions, (page 240)
5. Describe how to use scenario analysis in instances when data is scarce, (page 241)
6. Describe how to identify causal relationships and how to use Risk and Control
Self-Assessment (RCSA) and Key Risk Indicators (KRIs) to measure and manage
operational risks, (page 241)
7. Describe the allocation of operational risk capital to business units, (page 242)
8. Explain how to use the power law to measure operational risk, (page 243)
9. Explain the risks of moral hazard and adverse selection when using insurance to
mitigate operational risks, (page 243)
### 67. Governance Over Stress Testing
After completing this reading, you should be able to:
- [x] 1. Describe the key elements of effective governance over stress testing, (page 249)
- Key elements of effective governance and controls over stress testing include the governance structure, policies and procedures, documentation, validation and independent review, and internal audit.

-[x] 2. Describe the responsibilities of the board of directors and senior management in stress testing activities, (page 249)
- The board of directors has oversight for an organization’s key strategies and decisions and
is responsible and accountable for the entire organization. allowing the board to take actions that include adjusting capital levels, increasing liquidity, adjusting risks, or engaging in or withdrawing from certain activities.
- Senior management is accountable to the board and is responsible for the satisfactory implementation of the stress testing activities authorized by the board; To avoid inconsistencies, gaps, or problems, management must ensure that stress test assumptions remain transparent and are used in a clear manner.


- [x] 3. Identify elements of clear and comprehensive policies, procedures, and documentations on stress testing, (page 231)
```
• Describing the overall purpose of stress tests.
• Establishing consistent and adequate stress testing practices.
• Describing roles and responsibilities, including influences over external resources (e.g.,
vendors and data providers).
• Determining frequency and priority of stress testing activities.
• Outlining the stress test process, including scenario design and selection.
• Disclosing the validation and review process.
• Providing transparency to third parties regarding the stress testing process, which allows
third parties to evaluate the tests and their components.
• Indicating the use of stress tests and their users and any remedial actions.
• Updating and reviewing policies and procedures to remain consistent with the
institution’s risk appetite, risk exposures, and changing market conditions.
```


- [x] 4. Identify areas of validation and independent review for stress tests that require attention from a governance perspective, (page 252)
- Prudent governance should also incorporate ongoing validation and independent review of stress testing activities. These should be done in an unbiased manner using a critical review to ensure stress tests were conducted appropriately. Validation and independent review of stress tests should be incorporated into an institution’s overall validation and review processes.

- To enhance the usefulness of validating stress tests, institutions should include nonstress periods (i.e., the “good times” periods) in their models to test their predictive power.

- [x] 5. Describe the important role of the internal audit in stress testing governance and
control, (page 252)

- It is intended to assess the integrity and reliability of an institution’s policies and procedures, including those pertaining to stress tests.

- [x] 6. Identify key aspects of stress testing governance, including stress testing coverage, stress testing types and approaches, and capital and liquidity stress testing. (page 253)
```
Stress Testing Coverage
• Stress testing results may exclude important factors, including portfolios, liabilities, and
exposures. As a result, it is important that institutions provide appropriate coverage for
stress testing and document what factors are and are not covered.
• Stress testing coverage can be applied to individual exposures, to the entire institution, or
to various sublevels within an institution.
• Stress testing should incorporate the relationship between various risks and exposures,
and detect risk concentrations and causes of risks that could negatively impact the
institution.
• Coverage should be applied on both a short-term and long-term basis.
Stress Testing Types and Approaches
• When stress testing includes scenario analysis, the scenarios selected should be
sufficiently robust to be credible to stakeholders (internal and external).
• Scenarios should consider the firm-specific and system-wide impacts of stresses both
based on historical analysis and on hypothetical scenarios.
• Cumulative and knock-on effects should be carefully considered.
• For stresses that are done on a firm-wide basis, it is necessary for all business lines to use
the same stress assumptions to ensure consistency.
• Stress testing types should include those that extend beyond traditional risk expectations
(these include reverse stress tests that “break the bank”) and challenge the entire
institution’s viability. This is true even if estimation may be problematic.
Capital and Liquidity Stress Testing
• Capital and liquidity stress testing should be harmonized with overall strategy and
planning, and the results should be updated for all material results and events.
• Stress tests should consider the impact of multiple simultaneous risks on earnings, losses,
cash flows, capital, and liquidity.
• Stress testing should aid in contingency planning by identifying excess exposures and
areas where liquidity and capital positions can be strengthened, or by identifying actions
that are otherwise not possible during stressed times (i.e., raising capital).
• Stress testing should consider the effect on subsidiaries that encounter liquidity and
capital issues.
• Stress testing should also look at capital and liquidity problems that can arise
simultaneously and thereby magnify risks. For example, an institution may need to sell
assets at depressed market prices or incur funding costs at above-market rates.
• With respect to capital and liquidity funding costs, institutions should clearly articulate
their objectives.

```


```
LO 67.1
Stress tests should be conducted appropriately under adequate oversight as part of an
institution’s governance and controls.
Key elements of effective governance and controls over stress testing include the governance
structure, policies and procedures, documentation, validation and independent review, and
internal audit.
LO 67.2
The board of directors is accountable for the entire organization and must be sufficiently
knowledgeable about the organization’s stress testing activities.
Stress testing results inform the board of the institution’s risk appetite and profile and
operating and strategic decisions, and they may serve as early warning signs of upcoming
pressures.
Boards should actively challenge the results of stress tests and supplement them with other
tests as well as both quantitative and qualitative information.
Senior management, with oversight from the board, is responsible for establishing robust
policies for stress tests, which could supplement other risk, capital, and adequacy measures.
Management is also responsible for reviewing and coordinating stress test activities,
assigning competent staff, challenging results and assumptions, and incorporating remedies
to potential problems.
Senior management should ensure that there is a sufficient range of stress testing activities
to evaluate risks. Results should be benchmarked and regularly updated given that risks,
data sources, and the operating environment can change. An independent auditor should
verify test results.
Senior management should regularly report to the board of directors on stress testing results
in a clear and concise way, highlighting the key elements of the stress testing activities and
any limitations.
LO 67.3
Stress testing activities should be governed by clear and comprehensive policies and
procedures that are updated annually and documented in an appropriate manner.
Appropriate documentation allows senior management to track and analyze results over
time.
Documentation should include a description of the stress tests, main assumptions, results,
limitations, and any proposed remedies. Those responsible for documentation should be
given incentives given the complexity and time-consuming nature of preparing documents.
Documentation received from external parties should be reviewed.
Stress test policies, procedures, and documentation should address a range of issues,
including describing the purpose and process of stress test activities, establishing consistent
and adequate practices, defining roles and responsibilities, determining the frequency and
priority of stress testing activities, and describing proposed remedies.

LO 67.4
Ongoing validation and independent review of stress testing activities is an important
component of an institution’s governance. Validation and independent review should be
unbiased and critical, and they should form part of the institution’s overall validation and
review processes.
Results should be compared with appropriate benchmarks that reflect the institution’s risks
and exposures.
Stress tests for nonstress periods (i.e., “good times”) should be incorporated into an
institution’s model to test their predictive power and usefulness. Models used in nonstress
periods may require a different set of assumptions given changing risks, correlations, and
behavior by market participants.
Institutions do not need to fully validate stress tests, but limitations, challenges, and
proposed remedies should be communicated and disclosed in a transparent manner.
Validation and independent review should challenge the review process and the qualitative
components of the stress test, implement development standards, validate and implement
stress tests, and monitor performance.
LO 67.5
The internal audit assesses the integrity and reliability of policies and procedures. It should
verify that stress tests are conducted thoroughly and as intended, by staff with the relevant
expertise.
The internal audit should also review the procedures relating to the documentation, review,
and approval of stress tests. Any deficiencies should be identified.
LO 67.6
An institution’s governance framework should incorporate stress testing coverage, stress
testing types and approaches, and capital and liquidity stress testing.
Stress testing coverage should incorporate the relationship between risks and exposures in
the short term and long term, and detect risk concentrations that could negatively impact
an institution. Coverage can be applied to individual exposures, the entire institution, or
various sublevels within an institution.
Stress testing types and approaches should consider the firm-specific and system-wide
impacts of stresses from historical and hypothetical scenarios, and should include stresses
that challenge the entire institution’s viability. When stress testing is complemented with
scenario analysis, scenarios should be robust and credible.
Capital and liquidity stress testing should be harmonized with overall strategy and planning
and updated for all material results and events. The impact of multiple simultaneous
risks should be considered, including capital and liquidity problems that could arise
simultaneously and magnify risks. Objectives for capital and liquidity funding costs should
be clearly articulated. Excess exposures and areas should be identified where liquidity and
capital positions can be strengthened.

```

### 68. Stress Testing and Other Risk Management Tools
After completing this reading, you should be able to:
- [x] 1. Describe the relationship between stress testing and other risk measures, particularly in enterprise-wide stress testing, (page 260)
- Both stress tests and VaR measures [including economic capital (EC) measures] attempt to transform scenarios into loss estimates.
- 1. Stress tests usually define losses from an **accounting perspective**, while VaR/EC measures usually take a market view of losses (i.e., deducting the opportunity cost of equity capital).
- 2. Historically, stress tests have looked at **longer time horizons**, whereas VaR/EC measures have looked at point-in-time losses only.
- 3. Stress tests do not focus on probabilities, but instead focus on ordinal **rankings** such as “severe,” “very severe,” and “extremely severe.” In contrast, VaR/EC measures focus on cardinal probabilities when interpreting the results of using Monte Carlo simulation (i.e., complicated statistical models) or historical simulation (i.e., actual past results). For example, a 99% VaR loss is interpreted as a 1-in-100 event.
- Additionally, stress tests usually develop scenarios that are **conditional**. For example, regulatory stress tests tend to use the current period as a departure point in order to develop several hypothetical scenarios. In contrast, VaR/EC measures tend to develop unconditional scenarios.

- [x] 2. Describe the various approaches to using VaR models in stress tests, (page 261)
- expected loss = PD x LGD x EAD
  - where:
  - PD = probability of default
  - LGD = loss given default
  - EAD = exposure at default
- Merton model to simulate defaults and credit quality.
  - With this model, asset returns are simulated using a factor model and default would occur when the simulated asset value falls short of a threshold (related to the borrower’s leverage) at the end of one year.
- An alternate approach to measuring loss and likelihood of a particular scenario is to use stressed inputs.

- [x] 3. Explain the importance of stressed inputs and their importance in stressed VaR.
(page 261)
- The revised Basel market risk capital framework mandates the use of stressed inputs— for example, a stressed value at risk (SVaR) measure.
- The Basel III revisions mandate the use of stressed parameters to calculate the default risk capital charge for counterparty credit risk.
- The CVA represents the expected value or price of counterparty credit risk

- [x] 4. Identify the advantages and disadvantages of stressed risk metrics, (page 262)
- A key advantage of using stressed risk metrics is that they are conservative
- On the other hand, a key disadvantage is that risk metrics are stressed and will not necessarily respond to current market conditions. Instead, they will be impacted mainly by portfolio assets.


```
LO 68.1
Stress tests and value at risk (VaR) and economic capital (EC) measures attempt to
transform scenarios into loss estimates. The loss estimates’ distributions provide the basis to
compute VaR at a very high confidence level. Stress tests tend to look at far fewer scenarios
compared to VaR measures. Additionally, stress tests usually develop scenarios that are
conditional, while VaR/EC measures tend to develop unconditional scenarios.
LO 68.2
VaR/EC models compute expected losses using the following general formula:
expected loss = PD x LGD x EAD
In an attempt to assign a probability to a hypothetical or historical stress scenario, one could
determine where the stress test losses fall within the VaR/EC loss distribution. By assigning
probabilities to outcomes, the calculated probability from the loss distribution facilitates the
implementation of stress test results.
LO 68.3
Stressed inputs have been used in analyzing market risk and for both supervisory and
internal purposes within financial institutions. There is a mandated use of stressed inputs,
stress tests, and stressed parameters by the Basel Accords. Stressed VaR can be used to
analyze the potential losses for an investment portfolio. In addition, it can be used to
compute the capital charge for credit valuation adjustments (CVAs).
LO 68.4
A key advantage of using stressed risk metrics is that they are conservative. A key
disadvantage is that risk metrics will not necessarily respond to current market conditions.
```

### 69. Principles for Sound Stress Testing Practices and Supervision
After completing this reading, you should be able to:
- [x] 1. Describe the rationale for the use of stress testing as a risk management tool. (page 266)
- Stress testing is an important risk management tool that enables a bank to identify the potential sources of risk, evaluate the magnitude of risk, develop tolerance levels for risk, and generate strategies to mitigate risk.


- [x] 2. Describe weaknesses identified and recommendations for improvement in:
• The use of stress testing and integration in risk governance
• Stress testing methodologies
• Stress testing scenarios
• Stress testing handling of specific risks and products (page 267)
- [x] 3. Describe stress testing principles for banks regarding the use of stress testing and integration in risk governance, stress testing methodology and scenario selection, and principles for supervisors, (page 267)
- banks should use multiple techniques, ranging from sensitivity analysis (examining impact of one risk factor on a bank’s performance holding all other factors constant), to scenario analysis (examining various scenarios one at a time), to risk simulation (examining the impact of multiple risk factors and interactions simultaneously).

- Sound infrastructure should enable a bank to aggregate risk exposures quickly, alter methodologies, generate new scenarios, and conduct ad-hoc stress testing under extreme conditions.
- It should examine the impact of stress events (shocks) on risk factors while taking into consideration feedback and spillover effects due to correlations
- scenarios should involve testing both at the single entity (a specific product or business line) level and at the entire firm level.

```
LO 69.1
Stress testing is an important tool that enables a bank to identify, assess, monitor, and
manage risk. Recent financial turmoil has substantially increased the need for flexible,
comprehensive, and forward-looking stress testing.
LO 69.2
Major weaknesses and recommendations for stress testing and integration in risk
governances are as follows. Weaknesses: lack of involvement of board and senior
management, lack of overall organizational view, lack of fully developed stress testing, lack
of adequate response to crisis. Recommendations: Stress testing should form an essential
ingredient of overall governance of risk management plan, encompass multiple techniques
and perspectives, involve a sound infrastructure and regular assessment, produce written
policies and recommendations, and generate comprehensive firm and market-wide scenario
testing.
Stress testing methodologies were based on inadequate infrastructure, inadequate risk
assessment approaches, inadequate recognition of correlation, and inadequate firmwide
perspectives. Given these weaknesses, recommendations for improvement include
development of a comprehensive stress testing approach, identification and control of risk
concentrations, and multiple measurements of stress impact.
Stress testing scenarios lacked depth and breadth because they were based on mild shocks,
shorter duration, and smaller correlation effects among various markets, portfolios, and
positions.
Banks evaluated the risk of complex structured products based on the credit rating of
similar cash instruments. However, the nature, magnitude, and sources of risk for these
products are different from non-structured products. In order to identify, assess, monitor,
and control risk exposure of complex structured products, stress testing plans should utilize
all the relevant information about the underlying asset pool, market conditions, contractual
obligations, and subordination levels.
Historically, stress testing has not fully recognized funding liquidity risk and its correlation
with other risks in times of crises. Future stress tests should focus more on correlations of
various factors and risks, including funding liquidity risk.
LO 69.3
Principles for sound stress testing supervision include: assessing stress testing methods,
taking corrective actions, challenging firm-wide scenarios, evaluating capital and liquidity
needs, applying additional stress scenarios, and consulting additional resources.
```



