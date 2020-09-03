# Investment Projection with Monter Carlo Simulation

Tools and methods used on this project:

Plaid API, IEX API, Monte Carlo Simulation.

First a budget report was created using the Plaid API to fetch account's transactions data, then historical closing prices for a retirement portfolio were fetched with the IEX API to run Monte Carlo simulations to project the portfolio performance at 20 years. Finally, with the results from the simulation different financial scenarios were studies to come up with a retirement plan.

#### 1. Budget Analysis: Summarizing the transaction data from the budget analysis and including images for each chart and table produced.

Expenses per category

|  Category | Amount  |  
|-----------|:-------:|
| Food and Drink   |  3317.19 |  
|  Payment   | 6310.50  |   
| Recreation   | 235.50  |  
| Shops   |  1500.00 |  
|  Transfer  |  20537.34 |  
| Travel  |  41.52 |


The biggest expense was Transfer, the least was Travel


![supply_chain](/images/pie.png)

Frequency of each expense category

![supply_chain](/images/bars.png)

The following table summarizes the expenses per month. For the three month the expenses were $9135.51

|  Month| Expenses  |  
|-----------|:-------:|
| July   |  9135.51 |  
|  August   | 9135.51  |   
| September   | 9135.51 |  

#### 2. Monte Carlo Simulation

Monte Carlo simulation plot
![supply_chain](/images/3.png)

#### 3. Retirement Plan Forecasting

90% confidence interval for the ending returns
![supply_chain](/images/2.png)


Expected cumulative returns at 30 years for the 10th percentile 1.6377228612969736
Expected cumulative returns at 30 years for the 50th percentile 3.7765701646226226
Expected cumulative returns at 30 years for the 90th percentile 6.88829773148299

Expected portfolio return at the 10th percentile, initial investment of $20,000 is =  $52754.45722593948
Expected portfolio return at the 50th percentile, initial investment of $20,000 is =  $95531.40329245245
Expected portfolio return at the 90th percentile, initial investment of $20,000 is =  $157765.9546296598

With 4% withdraw rate from the retirement portfolio, projected retirement annual income  $1913.6860494840018, which is bigger than projected year income of $6085  

A 50% increase in the initial investment would generate a projected retirement annual income of $2870.529074226003. Which is bigger than the projected $1913.6860494840018

the cumulative returns for 5th, 50th and 90th percentiles on the simulation

![supply_chain](/images/1.png)


