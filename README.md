# R_Survival_Analysis
Survival analysis analyzes the expected duration of time until one event occurs. In this case, we try to identify the factors that would make customers stop subscribing to a service. Businesses could adjust their marketing strategy based on the result.

Nowadays a lot of businesses rely on the Subscription business model, so it is important to understand why people would stop subscribing to the service. To achieve this goal, we use R to conduct a survival analysis. 

In this project, we will review the credit status, rate plans, and payment terms. The result shows that credit status and rate plan would affect the duration, so the company can adjust its strategy to better serve those customers to gain a higher profit.


Case situation: A software company's profitability relies on how long its members pay for memberships. We want to analyze what factors affect customers’ length of payments.

    Raw Data
    Column1(customer id): ID
    Column2(start date): Date of activation 
    Column3(end-date):Date of deactivation 
    Column4(good_credit):1=yes, 0=no
    Column5(rate_plan):1, 2, or 3 (the bigger number, the higher rate)
    Column6(pay_type): A1, A2, B1, C1
    Column7(event_time): How many months did the subscription last (Target)
    Column8(event_type): 0=active, 1= churn

The result is shown below
We can use P-value to determine whether the result is significant.
"Good Credit" and "Rate Plan" both have an impact on event time.
![image](https://user-images.githubusercontent.com/58899897/194410790-dd6b9769-e912-4e8d-b158-3211201fcdd6.png)

![image](https://user-images.githubusercontent.com/58899897/194411309-c90372cf-6cb3-4026-97de-2c774d98165b.png)



