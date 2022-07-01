# King_County_House_Pricing_Analysis
 
# King County House Pricing analysis
#### Data Science Project, July 2022
#### By **Nelly Ng’eno**
## Introduction
I have been tasked with analyzing the data of houses in King County. My goal is to make predictions about the sale price of houses based on certain variables or features,so that they can be used to make profitable decisions by a housing development company. This project provides actionable insights with respect to what kind of home renovations the home owners might make with the goal of maximizing the sale price of their home.
## Business problem
There are many King County residents that have decided to sell their homes and want to renovate their home to increase its resale value because the housing market has become an hot cake. However, the home owners don't know what factors are important for determining a home's value and require information to inform them on what renovations to make. Using home sale price and other housing data from King County, I will identify which potential renovations would best maximize home sale price.
## Data
This analysis leverages the King County House Sales data which contains data on home sales from King County,from the years 2014-2015. The data represents a number of home characteristics.The target variable of the analysis is home price.
##Method
1. Data Cleaning- removal of outliers, creating dummy variables from categorical data, converting data to integers,dropping of correlated variables
2. Exploratory Data analysis techniques
##Regression analysis
My final model
 
 
Based on the adjusted R squared value of 0.807 meaning that 80% of the variability in price is explained by the variables. and the large F statistic, I can conclude that the correlation between the model and dependent variable is statistically significant, and can be used as a tool to help predict housing prices, and more importantly, identify home characteristics that affect home sale price. The final model is also notably better than the baseline model, with a higher R squared and more adherence to the normality and homoskedasticity assumptions. While the model is not perfect, I believe it could be generalized beyond the current data effectively with data from similar counties to King County, and that it would benefit any homeowner in similar areas.

## Visualization 
Was renovated vs price analysis

 
As per the figure above the price of renovated housed are higher than the prices of non renovated houses.A renovated house will lead to an increase of price by $27897.36.
Number of floors Vs Home Price
 
With a positive coefficient of 40326.13, increasing the number of floors in a home by one could result in increasing the sale price of the home by over $40,000
Bathrooms vs home price analysis
 
With a positive coefficient of 22999.71, increasing the number of bathrooms in a home by one could result in increasing the sale price of the home by over $20,000
condition vs price analysis
 

increasing the condition of a home by one level on a scale from 1-5, could result in an increase in home price of over $15000.
## Conclusion
•	Home renovation. As evidenced by a positive coefficient of 27897.36,means that renovating a home could result in an increase in home price of over $20,000. Based on the results, I would recommend that homeowners should renovate their homes.
•	Home condition has a positive coefficient of 16290.82, increasing the condition of a home by one level on a scale from 1-5, could result in an increase in home price of over $10,000. Condition is defined by King County as an index from 1 to 5 based on the overall condition of the home. Homeowners should focus on improving the condition of the home, potentially by replacing appliances and features of the home.
•	Home bathrooms. Evidenced by a positive coefficient of 22999.71, increasing the number of bathrooms in a home by one could result in an increase in home price of over $20,000. Homeowners should consider adding bathrooms as a tangible way of increasing their homes sale price.
•	Home Floors. Represented by a coefficient of 40326.13, adding floors to a home could potentially have a positive impact on sale price.home owners should consider adding more floors to increase their home sale price.

## Technologies Used
Jupyter notebook

