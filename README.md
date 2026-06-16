🚚 AI Route Optimization Impact Analysis  
📌 Project Overview  

This project analyzes whether AI Route Optimization improves delivery performance and validates management's claim that AI-powered route planning reduces delivery time.  

Using statistical analysis and hypothesis testing, the project evaluates delivery operations data and provides business recommendations based on evidence rather than assumptions.  

🎯 Business Problem  

Management claims that:  

"AI Route Optimization reduces delivery time."  

As a Data Analyst, the goal is to verify this claim using probability, statistics, hypothesis testing, and exploratory data analysis.  

📊 Dataset Information  
  
Dataset Size  

Rows: 500  
Columns: 8  
Features  
Column	Description  
Order_ID	Unique order identifier  
Delivery_Time_Min	Delivery time in minutes  
Distance_KM	Distance traveled  
Order_Value_INR	Order value in INR  
Delivery_Partner_Rating	Partner performance rating  
Customer_Rating	Customer satisfaction rating  
Traffic_Level	Traffic condition (Low, Medium, High)  
AI_Route	Whether AI route optimization was used
  
🛠 Technologies Used  
Python  
Pandas  
NumPy  
Matplotlib  
Seaborn  
SciPy Statistics  

📈 Statistical Concepts Covered  
Descriptive Statistics  
Variable Classification  
Continuous Variables  
Discrete Variables  
Categorical Variables  
Probability  
Probability of AI Route Usage  
Probability of Delivery Time > 40 Minutes  
Inferential Statistics  
Chi-Square Test of Independence  
Normality Testing  
Shapiro-Wilk Test  
Skewness & Kurtosis  
Q-Q Plot Analysis  
Confidence Intervals  
One-Sample T-Test  
Independent Two-Sample T-Test  
Standardization  
Standard Deviation Analysis  
Z-Score Calculation  

🔍 Business Questions Solved  
1. Variable Classification  

Identify:  

Continuous  variables  
Discrete variables  
Categorical variables  
2. AI Route Adoption Rate  
 
Calculate the probability that a randomly selected order used AI Route Optimization.  

3. Traffic vs AI Route  

Determine whether traffic conditions influence AI route usage using a Chi-Square Test.  

4. Delivery Time Distribution  
 
Check whether delivery time follows a normal distribution using:  

KDE Plot  
Q-Q Plot  
Shapiro-Wilk Test  
Skewness  
Kurtosis  
5. Late Delivery Probability  

Estimate the probability that delivery time exceeds 40 minutes.  

6. Standard Deviation Analysis  

Calculate:  

±1 Standard Deviation Range  
Z-Score for a 50-minute delivery  
7. Confidence Interval Estimation  

Estimate the average future delivery time using a 95% Confidence Interval.  

8. Company Claim Validation  

Test whether the average delivery time equals 30 minutes using a One-Sample T-Test.

9. AI Route Effectiveness

Compare delivery times between:  

AI Route Deliveries  
Non-AI Route Deliveries  

Using an Independent Two-Sample T-Test.    
