# R_Survival_Analysis
Nowadays a lot of businesses rely on the Subscription business model, so it is important to understand why people would stop subscribing the service. To achieve this goal, we use R to conduct a survival analysis. 

Case situation: A software company's profitability relies on how long its members pay for memberships. We want to conduct an analysis to help the business to understand what factors affect customers’ length of payments? 

    Raw Data
    Column1(costomer id): ID
    Column2(start date): Date of activation 
    Column3(end date):Date of deactivation 
    Column4(good_credit):1=yes, 0=no
    Column5(rate_plan):1, 2, or 3 (the bigger number, the higher rate)
    Column6(pay_type): A1, A2, B1, C1
    Column7(event_time): How many months did the subscription last (Target)
    Column8(event_type): 0=active, 1= churn

The Result is shown below
We can use P-value to determine whether the result is significant.
"Good Credit" and "Rate Plan" both have impact on event time.
![image](https://user-images.githubusercontent.com/58899897/194410790-dd6b9769-e912-4e8d-b158-3211201fcdd6.png)

![image](https://user-images.githubusercontent.com/58899897/194411309-c90372cf-6cb3-4026-97de-2c774d98165b.png)



