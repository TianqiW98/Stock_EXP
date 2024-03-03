# Self Project EXP Stock Status Repository
Creator: Xinghe ☆☆☆

Project Description: Mid-Long Term Investment Strategy based on EXP Stock Status Recognition System - Monthly Decision Model
* Model Description:
    * I am gonna test all stock data in last month data to decide the gradient and renew weekly, helping me to decide on each Friday if I need to move in or not
    * Using weekly generated gradient, I am developed a system to match its accuracy under some creterion for 1. Increasing Gradient 2. EXP matching 3. Non-linear Polynomial Trend
      
* Data Collection
    * Automatic Data Input from whose API?
      
* **Model Basic Investment Consideration**
    * Transition From Linear Fit to Nonlinear One (On Positive Aspect)
        * Gradient Requirement: 18%
          
    * Variance Stability:
        * The fifth week volatility should keep the same as the past month average one based on 95% confidence intervel
        * The variance could be smaller than the previous month's
          
    * Selling out time pt.:
        * If the the trend showing 22% decreasing on the Friday, the model will give out signal on selling out the stock
        * If the turnover rate is higher than 70%, the model will give out signal on selling out the stock
