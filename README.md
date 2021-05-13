# Inflation Rate Analysis
---
###### Authors: Rikin, Tyler, Juan, Marcus, Emmanuel

## Intro : In this project, we set out to visualize and analyze inflation in the United States, and attempt to understand which other types of economic metrics lead to, correlate with, and are a result of inflation. We looked at various different metrics such as; GDP, Unemployment Rate, Tax Rates, Money Supply, Bank Borrowing, Income Per Capita, and more. 
---
### Step 0: Understanding Inflation

Before we jumped into coding, we took a deep dive into what Inflation is, and what types of factors may be related to inflation. Inflation is the rate at which the value of the USD falls, hence the amount of "stuff" one dollar can buy decreases. It is common to use the change in Consumer Price Index or Producer Price Index to mark inflation. 

### Step 1: Pulling Data

We used various different API's to pull in all these metrics. We quickly learned that the Federal Reserve Economic Data API would be a vital tool in this project. We were able to access data from FRED using QUANDL's python API.

### Step 2: Data Descriptions

# Inflation:

Consumer Price Index (CPI) - measure the price of a selection of goods and services for a typical consumer.

Producer Price Index (PPI) – measures the prices for all goods and services at the wholesale level. It is like the consumer price index but it is measuring the prices the producers have to pay.

# Money Supply:

M1 - M1 consists of (1) currency outside the U.S. Treasury, Federal Reserve Banks, and the vaults of depository institutions; (2) demand deposits at commercial banks (excluding those amounts held by depository institutions, the U.S. government, and foreign banks and official institutions) less cash items in the process of collection and Federal Reserve float; and (3) other liquid deposits, consisting of OCDs and savings deposits (including money market deposit accounts). 

M2 - consists of M1 plus small-denomination time deposits (time deposits in amounts of less than 100,000, minus IRA and Keogh balances at depository institutions; and balances in retail MMFs less IRA and Keogh balances at MMFs.

Personal Savings - Personal income less personal outlays and personal current taxes.

Personal Savings Rate - Savings percentage of disposable income.

Velocity of Money - The velocity of money is the frequency at which one unit of currency is used to purchase domestically- produced goods and services within a given time period. It is the number of times one dollar is spent to buy goods and services per unit of time. If the velocity of money is increasing, then more transactions are occurring between individuals in an economy.


# Unemployment:

Unemployment Rate - Percent Seasonally Adjusted, the unemployment rate represents the number of unemployed as a percentage of the labor force.

# GDP:

GDP Growth - GDP measures the value of the final goods and services produced in the United States (without double counting the intermediate goods and services used up to produce them). GDP growth is the year over year percentage change.

Personal Income - is a line item of GDP. It is the amount of money we make per person.


#### Step 3: Analysis

Quick thoughts - The savings rate has been declining since the end of WWII, while the absolute dollars saved by US citizens has increased over that period of time. There haven't been enough dollars circulating in the economy to generate a higher savings rate. iF there was, the savings rate and absolute dollar amount would be up. But the lack of money velocity is confirmed by muted inflation over this period of time.

Velocity is somewhat consistent over a 40 year period, but today it is significantly below the mean due to the virus. Now that life is going back to normal, it should revert to the mean.

Finally, history shows inflation volatility centered around wars and unplanned events like the great recession/depression. Moving forward, increased money supply, average circulation at the minimum, paired with an exogoneous event (coronavirus), should increase the odds of future inflation.

Mean reversion for velocity + increased money supply + (history of exogenous event's effect on inflation) = inflation?