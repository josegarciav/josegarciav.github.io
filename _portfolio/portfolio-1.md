---
title: "Budget Allocation Project"
excerpt: "Machine Learning project focusing on predicting the volume of hectoliters to be sold for different products over two horizon periods, and then optimizing the net revenue while minimizing the investment budget (discounts).<br/><img src='/images/portfolio-1.png'>"
collection: portfolio
---

This project was part of a global hackathon. The project consisted on understanding how much budget should be allocated across various promotion categories per SKU to maximize overall profitability, making sure the investment in the promotion was paying off. We were tasked with assisting the revenue management team in determining:

- The estimated volume and net revenue resulting from the investments planned by the revenue management team.
- The optimal investments recommended by an efficient budget allocation algorithm, across various promotion categories and for each SKU. The goal here is to maximize the net revenue increase while minimizing the total investments required.

We were given a set of constraint datasets that pertained to the following:

* Volume variation constraints per predicted horizon
* Maximum discount to be given per category
* We were also given macroeconomic data such as GDP, CPI, unemployment rate, and gross domestic savings, as a means to aid us in our volume predictions.

We used the XGBoost algorithm for the regression problem and optimized its hyperparameters using Optuna. The trained regression model was used for volume predictions.

Optimization Approach
----
To optimize budget allocation, we employed non-linear constraint optimization using the COBYLA algorithm. The objective function was constructed to:

* Maximize net revenue.
* Minimize the investment budget (discounts).
* Introduce a lambda value to balance the trade-off between net revenue and discount values.
* Account for business constraints and variation predictions.


Results
----

We evaluated the model's performance using the following key metrics:

* Mean Absolute Percentage Error (MAPE): 21.66%
* Root Mean Square Error (RMSE): 0.9163
* Mean Absolute Error (MAE): 0.5277

![One result](/images/portfolio-1.png)

Here we can see one optimized result for one of the SKU's given, in which we can globally see the demand curves per type of promotion predicted, as well as the optimal balance between discount and net revenue. The green star represents the point in which not only we are minimizing the investment (discounts to be given), but also maximizing the net revenue associated with that investment.



You can find more about this project [here](https://github.com/josegarciav/Hackathon_Global_ABInBev).
