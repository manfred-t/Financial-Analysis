# Financial Analysis Project

This project dealt with a hypothetical financial problem regarding investment strategies.

## Problem Guidelines

There exists three different investement strategies in this scenario.
1. An investment account governed by compound interest with an annual effective discount rate of 3%.
2. An investment account with a force of interest equal to $\Large\frac{0.04}{1+0.5t^2}$.
3. An investment account governed by the accumulation function $\Large a^{III}(t) = (1 - .005t^2)^{-1} $

The money in the account may be transfered at any time. Assuming we start with $10,000 to invest at time t=0, what is the maximum amount we can accumulate at time t = 5? 

## Breakdown

We are given three different investment methods and are asked for the optimal investment strategy. Since we are seeking maaximal profits, the approach for this problem is to look at the force of interest for each investment method. This way, we can directly compare the time value of each investment. We can use that to determine which account the money should be held in at a given time period.

#### Account 1

The first account has compound interest with an effective discount rate of 3%. The discount rate can be converted to an equivalent interest rate through the formula $i = \Large\frac{d}{1-d}$. This gives us an interest rate of $\Large\frac{0.03}{0.97}$. We can use this to find the force of interest, shown below.

#### Account 2

The second account has a given force of interest of $\Large\frac{0.04}{1+.05t^2}$.

#### Account 3

The third account gives the accumulation function $\Large a^{III}(t) = (1 - .005t^2)^{-1}$. Using this, we can find the force of interest using the formula $\Large\frac{a’(t)} {a(t)}$.

<img title="a title" alt="Force of Interest" src="/images/boo.svg">







