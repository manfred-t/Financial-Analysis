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

Force of Interest:

<img title="a title" alt="Force of Interest" src="/images/foi_FA.png">


After we have calculated all of the forces of interest, we plot them to see which accounts have the most value at a given time, as shown below in diagram 1.

<img title="a title" alt="Force of Interest" src="/images/graph_FA.png">

The x-axis represents how much time has passed; in this problem, we are looking from t=0 to t=5. The y-axis represents the force of interest, delta t. The higher it is, the more interest you receive at that given time. Thus we are looking for the highest force of interest at each time period. We can find three distinct time periods. The first, from t=0 to t=2.5029, uses account 2. The second, from t=2.509 to t=2.916, uses account 1. The third, from t=2.916 to t=5, uses account 3. Knowing the highest force of interest allows us to use the associated accumulation function in order to calculate the amount of interest earned. We can use the force of interests to find the accumulation function for each time period, using the formula:

<img title="a title" alt="Force of Interest" src="/images/accum_FA.png">

We can use these accumulation functions alongside the initial investment of 10000 in order to find out the maximum amount it can be turned into by the end of t=5.

<img title="a title" alt="Force of Interest" src="/images/total_FA.png">

This leaves us with a final amount $12,140.26, the maximum amount of money that can be accumulated at time t=5.



## Citations

This example problem was taken from Mathematical Interest Theory (2008) by Leslie Jane Federer Vaaler and James Daniel.

