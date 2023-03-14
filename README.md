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


* Towards the lefthand side, we have lower risk and higher diversity.

* Towards the righthand side, we have higher risk and lower diversity.

* We have the optimal allocation of stocks corresponding to each risk level.

* For our analysis, we would be considering the risk value of 0.000205 and the corresponding stocks chosen are McDonald's, Autodesk and Verisk. This risk value has been chosen as these 3 stocks belong to 3 different sectors and their allocation proportion sums to 1 approximately.

* We can see that the 3 stocks chosen by the MPT (Modern Porfolio Theory) model are **McDonald's, Autodesk & Verisk.**


### **Results**

<img width="706" alt="image" src="https://user-images.githubusercontent.com/70052374/224860494-88ea2efb-cdf9-463e-9b1b-e5cf403c88fe.png">


* For the Buy_and_Hold strategy, the Aggregate Value of the investment on November 1st 2022 was **$93,253.**

* For the Momentum Trading strategy, the Aggregate Value of the investment on November 1st 2022 was **$88,033.**

* If we invested in S&P 500 index, the Aggregate Value of the investment on November 1st 2022 was **$90,356.**

* Therefore, if we used the 'Buy & Hold Strategy' or the 'Momentum Trading Strategy' based on the chosen portfolio allocation, we would be losing money. If we invest in S&P 500 index, we would be losing about $10,000 approx.

* So we can conclude that **Buy_and_Hold strategy** helps to retain the maximum value for investment of the 3 strategies.


### **Conclusions**

* For the Portfolio Allocation Model, we have used binary constraints to ensure that we select one and only one stock from each sector.

* Decreasing the max limit for risk and reducing the step size gave us good results as the data collected is on a daily basis (for 5 years). Using the parameter analysis, the optimal risk was chosen, and was used for further analysis.

* We considered 5 different pairs of values of moving averages to determine the best Momentum Trading Strategy for each stock. The best strategy for each stock was decided based on the system return value for all the combinations.

* Based on the analysis for 2022, we got to know that 'Buy and Hold' strategy worked better for the chosen portfolio on the whole when compared to Momentum Trading strategy.

* Coming to the Individual stocks, for Verisk, the Momentum Trading Strategy worked better than Buy and Hold Strategy. For the other two stocks (McDonald's & Autodesk), Buy and Hold strategy worked better than Momentum Trading Strategy.

* Investment strategies play a vital role for investors; they can be goal-oriented and hence can help the investors make investment decisions based on their goals. The best investing strategies are the ones that have higher returns & lower risks. However, there is always a trade-off.

* The obtained strategy may vary on several factors, including but not limited to, one’s investment goals such as short term or long term, asset sector considered, the timeframe considered, and the risk ceiling considered. 
