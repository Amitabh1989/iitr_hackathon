# iitr_hackathon
My code submission on Coupons prediction for IITR hackathon organized by Times TSW.

Machine Learning Hackathon 
Problem Statement 
You are hired as a data scientist at a leading shopping mall in the country. The shopping mall has tied 
up with different restaurants/bars to provide discount coupons to all its customers. The coupons 
increase the footfalls at these restaurants and help the shopping mall to attract more customers. 
The organization has been relying upon simple guidelines to determine what coupons are to be 
provided to the customers, however, the organization feels that they need a more robust model to 
determine whether a customer will accept the recommended coupon or not to improve the use 
rate. The organization plans to use a mix of client's details that they have captured to create this 
model. 
You are provided with the historical data of the recommended coupons along with customer 
details in the previous years and your task is to come up with a model which would be able to 
predict whether a customer will accept the recommended coupon. 
Data Description 
train data - 10,147 records 
test data - 2,537 records 
 destination: No Urgent Place, Home, Work 
 passenger: Alone, Friend(s), Kid(s), Partner (who are the passengers in the car) 
 weather: Sunny, Rainy, Snowy 
 temperature:55, 80, 30 
 time: 2PM, 10AM, 6PM, 7AM, 10PM 
 coupon: Restaurant (<$20), Coffee House, Carry out & Take away, Bar, Restaurant($20-$50) 
 expiration: 1d, 2h (the coupon expires in 1 day or in 2 hours) 
 gender: Female, Male 
 age: 21, 46, 26, 31, 41, 50plus, 36, below21 
 maritalStatus: Unmarried partner, Single, Married partner, Divorced, Widowed 
 has_Children:1, 0 
 education: Some college - no degree, Bachelors degree, Associates degree, High School 
Graduate, - Graduate degree (Masters or Doctorate), Some High School 
 occupation: Unemployed, Architecture & Engineering, Student, Education&Training&Library, 
Healthcare Support, Healthcare Practitioners & Technical, Sales & Related, Management, 
Arts Design Entertainment Sports & Media, Computer & Mathematical, Life Physical Social 
Science, Personal Care & Service, Community & Social Services, Office & Administrative 
Support, Construction & Extraction, Legal, Retired, Installation Maintenance & Repair, 
Transportation & Material Moving, 
 Business & Financial, Protective Service, Food Preparation & Serving Related, Production 
Occupations, 
 Building & Grounds Cleaning & Maintenance, Farming Fishing & Forestry 
 income: $37500 - $49999, $62500 - $74999, $12500 - $24999, $75000 - $87499, 
 $50000 - $62499, $25000 - $37499, $100000 or More, $87500 - $99999, Less than $12500 
 Bar: never, less1, 1-3, gt8, nan,4-8 (feature meaning: how many times do you go to a bar 
every month?) 
 CoffeeHouse: never, less1, 4-8, 1-3, gt8, nan (feature meaning: how many times do you go to 
a coffeehouse every month?) 
 CarryAway:n4-8, 1-3, gt8, less1, never (feature meaning: how many times do you get takeaway food every month?) 
 RestaurantLessThan20: 4-8, 1-3, less1, gt8, never (feature meaning: how many times do you 
go to a restaurant with an average expense per person of less than $20 every month?) 
 Restaurant20To50: 1-3, less1, never, gt8, 4-8, nan (feature meaning: how many times do you 
go to a restaurant with average expense per person of $20 - $50 every month?) 
 toCoupon_GEQ15min:0,1 (feature meaning: driving distance to the restaurant/bar for using 
the coupon is greater than 15 minutes) 
 toCoupon_GEQ25min:0, 1 (feature meaning: driving distance to the restaurant/bar for using 
the coupon is greater than 25 minutes) 
 direction_same:0, 1 (feature meaning: whether the restaurant/bar is in the same direction 
as your current destination) 
 direction_opp:1, 0 (feature meaning: whether the restaurant/bar is in the same direction as 
your current destination) 
 Y:1, 0 (whether the coupon is accepted)
