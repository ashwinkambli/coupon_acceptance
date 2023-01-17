# coupon_acceptance
A data analysis of coupon acceptance data across various types of drivers

## Overview
This repo is for the submission of my assignment for the ML & AI course work. 
In this assignment I analysed data made available to us by Amazon Mechanical Turk and includes various data points about drivers and whether they accepted the coupons or not. 
The data points include attributes such as: 
-- Age of the driver, 
-- Sex of the driver, 
-- Education of the driver, 
-- occupation field and income of the drivier, 
-- How frequently did the driver visit a bar/coffee house/restaurant, etc
-- How far away is the driver from the restaurant for which the coupon was issued and are they driving towards or away from the restaurant
-- Coupon type: Bar, Restaurant (expensive, cheap, etc), Coffee House, etc

I was able to analyse the acceptance data for 2 types of coupons: Bar and Coffee House. 

## Here are my observations: 
### Bar Coupon observations:
-- Carryout and Take Away and Restaurant(<20) coupons get used the most while Bar coupons get used the least.
-- A total of **41%** of the folks who were offered a bar coupon accepted it. This is lower compared to the overall average of **56%**
-- You are twice as likely to accept a Bar coupon if you are:
  -- frequent the bar more than three times a month, or
  -- above 25 years of age and frequent the bar more than once a month
  -- frequent the bar more than once a month, and are not employed in the Farming, Fishing, or Forestry industry, and also happen to not be travelling with kids as passengers.
  -- frequent cheap resturants more than 4 times a month and earn less than 50K
Overall, there seems to be strong correlation between the number of times you visit a bar and your likelihood of accepting a bar coupon. 

### Coffee House coupon observtions:
-- Even tough we have the most data points available for Coffee House coupons (~ 4K), our ability to predict whether someone will accept a cofffee house coupon or not is not better than our ability to predict the outcome of a coin toss. So, I would like to further investigate the coffee house coupons
-- Coffee house coupons are most efficient if they are issued around 10 am
-- Your best bet for a coffee house coupon acceptance is if you give it to a 20 year old. But, the acceptance rate flattens out between 45% - 55% for all other age group demographics.


## Links
Worksheet: https://github.com/ashwinkambli/coupon_acceptance/blob/main/Will%20a%20Customer%20Accept%20the%20Coupon.ipynb
Data: https://github.com/ashwinkambli/coupon_acceptance/blob/main/data/coupons.csv
