## **Comparison of Investment Strategies for Stocks : Optimizing Investments**


### **Project Description**

The goal is to allocate **$100,000** into stocks while taking into account the risk tolerance, which is measured by volatility, to maximize the expected return. An optimal mix of stock allocation will be calculated for each risk level to maximize profits. Well-balanced and diversified portfolios have low-risk levels, resulting in a lower potential profit. Highly volatile portfolios with narrow asset mixes will have high-risk levels.

The main objective is to create a portfolio of stocks that appropriately balances conflicting risk and profit, and to compare different investment strategies : 

a) Buy and Hold Strategy

b) Momentum Trading Strategy

c) Indexed Investing Strategy



### **Stocks Chosen**

We have chosen the following stocks for our analysis :

<img width="571" alt="image" src="https://user-images.githubusercontent.com/70052374/224860009-2f57c4a3-a671-4224-8e3d-b43202124b96.png">



### **Optimal Stock Allocation for Different Risk Levels**

<img width="283" alt="image" src="https://user-images.githubusercontent.com/70052374/224859820-03f28023-424c-4d37-be74-4d6e7622d490.png">


* Towards the left-hand side, we have lower risk and higher diversity.

* Towards the right-hand side, we have higher risk and lower diversity.

* We have the optimal allocation of stocks corresponding to each risk level.

* For our analysis, we would be considering a risk value of **0.000205** and the corresponding stocks chosen by the MPT (Modern Porfolio Theory) model are **McDonald's, Autodesk and Verisk**. This risk value has been chosen as these 3 stocks belong to 3 different sectors and their allocation proportion sums up to 1 approximately.



### **Efficient Frontier**

<img width="347" alt="image" src="https://user-images.githubusercontent.com/70052374/226145242-6ac20d3a-cc76-4df3-9e2f-5707782a48a7.png">



* The Efficient Frontier shows Risk (X) vs. Return (Y).

* After a certain point, taking on more risk doesn't increase your returns! This occurs at ~Risk = **0.00055** which achieves a maximum return of around **0.132% (0.00132)**.

* Any point on the Efficient Frontier represents an optimal allocation based on your risk tolerance.



### **Momentum Trading Strategy**

* We have considered 5 different pairs of moving averages for the selected portfolio.

 a) 9-Day/21-Day Moving Average Strategy
 
 b) 5-Day/13-Day Moving Average Strategy
 
 c) 50-Day/200-Day Moving Average Strategy for Long Term Investors
 
 d) 21-Day/55-Day Moving Average Strategy
 
 e) 15-Day/30-Day Moving Average Strategy






* Best Strategy For Each of the 3 stocks in the selected portfolio (based on historic stock value (daily data) from January 1 2017 to December 31 2021) :

 a) For **McDonald's**, the highest return corresponds to the **21-Day/55-Day** strategy.
 
 b) For **Autodesk**, the highest return corresponds to the **5-Day/13-Day** strategy.
 
 c) For **Verisk**, the highest return corresponds to the **15-Day/30-Day** strategy.


### **Results**

* We have assumed that we have invested **$100,000** on January 1 2022.

* Based on the chosen allocation of the stocks from the MPT model corresponding to a risk value of **0.000205** , the amount invested in McDonald's would be **$27,168.5** , the amount invested in Autodesk would be **$32,814.4** and the amount invested in Verisk would be **$40,017.1**.

<img width="286" alt="image" src="https://user-images.githubusercontent.com/70052374/226147520-fa9a5cf5-8320-474d-a94f-552dedcd651d.png">




* We have evaluated the Aggregate value of the porfolio at the beginning of each month until November 1 2022 (as shown below) for all 3 strategies.

<img width="706" alt="image" src="https://user-images.githubusercontent.com/70052374/224860494-88ea2efb-cdf9-463e-9b1b-e5cf403c88fe.png">


* For the Buy_and_Hold strategy, the Aggregate Value of the investment on November 1st 2022 was **$93,253.**

* For the Momentum Trading strategy, the Aggregate Value of the investment on November 1st 2022 was **$88,033.**

* If we invested in S&P 500 index, the Aggregate Value of the investment on November 1st 2022 was **$90,356.**

* Therefore, if we used the 'Buy & Hold Strategy' or the 'Momentum Trading Strategy' based on the chosen portfolio allocation, we would be losing money. If we invest in S&P 500 index, we would be losing about $10,000 approx.

* So we can conclude that **Buy_and_Hold strategy** helps to retain the maximum value for investment of the 3 strategies.


### **Conclusions**

* For the Portfolio Allocation Model, we have used binary constraints to ensure that we select one and only one stock from each sector.

* Decreasing the max limit for risk and reducing the step size gave us good results as the data collected is on a daily basis (for 5 years). Using parameter analysis, the optimal risk was chosen, and was used for further analysis.

* We considered 5 different pairs of values of moving averages to determine the best Momentum Trading Strategy for each stock. The best strategy for each stock was decided based on the system return value for all the combinations.

* Based on the analysis for 2022, we got to know that **'Buy and Hold Strategy'** worked better for the chosen portfolio on the whole when compared to Momentum Trading strategy.

* Coming to the Individual stocks, for Verisk, the Momentum Trading Strategy worked better than Buy and Hold Strategy. For the other two stocks (McDonald's & Autodesk), Buy and Hold strategy worked better than Momentum Trading Strategy.

* Investment strategies play a vital role for investors; they can be goal-oriented and hence can help the investors make investment decisions based on their goals. The best investing strategies are the ones that have higher returns & lower risks. However, there is always a trade-off.

* The obtained strategy may vary on several factors, including but not limited to, one’s investment goals such as short term or long term, asset sector considered, the timeframe considered, and the risk ceiling considered. 
