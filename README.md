# Starbucks-Customer-Survey-Analysis
https://www.kaggle.com/mahirahmzh/starbucks-customer-retention-malaysia-survey
# Data Understanding
Dataset Description
This dataset is composed of a survey questions of over 100 respondents for their buying behavior at Starbucks.Income is show in Malaysian Ringgit (RM)
Context
Predict behavior to retain customers. You can analyze all relevant customer data and develop focused customer retention programs
Content
Demographic info about customers – gender, age range, employment status, income range
Their current behavior in buying Starbucks
Facilities and features of Starbucks that contribute to the behavior
Inspiration
What are the characteristic of customer that will continue buying Starbucks? 

# Technical
* Language : Python (filetype: .ipynb)

# Data Field
* Data Columns
* Timestamp
* Your Gender
* Your Age
* Are you currently....?
* What is your annual income?
* How often do you visit Starbucks?
* How do you usually enjoy Starbucks?
* How much time do you normally spend during your visit?
* The nearest Starbucks's outlet to you is...?
* Do you have Starbucks membership card?
* What do you most frequently purchase at Starbucks?
* On average, how much would you spend at Starbucks per visit?
* How would you rate the quality of Starbucks compared to other brands (Coffee Bean, Old Town White Coffee..) to be:
* How would you rate the price range at Starbucks?
* How important are sales and promotions in your purchase decision?
* How would you rate the ambiance at Starbucks? (lighting, music, etc...)
* You rate the WiFi quality at Starbucks as..
* How would you rate the service at Starbucks? (Promptness, friendliness, etc..)
* How likely you will choose Starbucks for doing business meetings or hangout with friends?
* How do you come to hear of promotions at Starbucks? Check all that apply.
* Will you continue buying at Starbucks?

RENAME COLUMN AND REMOVE COLUMN TIME STAMP

* Your Gender  =  Gender 
* Your Age  = Age
* Are you currently....?  = Working_Status
* What is your annual income? = Annual_Income
* How often do you visit Starbucks? = Visit_Duration 
* How do you usually enjoy Starbucks? = How do you usually enjoy Starbucks?
* How much time do you normally  spend during your visit? = Spending_Time
* The nearest Starbucks's outlet to you is...? = Outlet_Location
* Do you have Starbucks membership card? = Member
* What do you most frequently purchase at Starbucks? =   Frequent_Purchase
* On average, how much would you spend at Starbucks per visit? = Average_Spending
* How would you rate the quality of Starbucks compared to other brands (Coffee Bean, Old Town White Coffee..) to be = Product_Rating 
* How would you rate the price range at Starbucks? = Price_Rating
* How important are sales and promotions in your purchase decision?’ = Promotion_Rating 
* How would you rate the ambiance at Starbucks? (lighting, music, etc...) = Ambiance_Rating
* You rate the WiFi quality at Starbucks as..=  Wifi_Rating
* How would you rate the service at Starbucks? (Promptness, friendliness, etc..) = Service_Rating
* How likely you will choose Starbucks for doing business meetings or hangout with friends? = Hangout/business meetings_Place_Rating 
* How do you come to hear of promotions at Starbucks? Check all that apply. = Promotion_Tools 
* Will you continue buying at Starbucks = Loyal_Customer

# CONCLUSION

In this notebook, Starbucks Malaysia customers are analyzed through a collection of data from the Survey on purchasing behavior. For this task, a visual exploration of the data was created using Bar Plots and other visualization techniques used to see the relationships between different categories of data and can easily be seen.

With this, some great insights could be obtained about the costumers. First, with the initial exploratory data, we could conclude that:
 * The costumers are well balance between Male and Female
 * Most of the customers are young people, ranging between 20 and 29 years old, and generally are emplyoed and Students with income below RM 25,000.
 * Average spending less than 20RM
 * Data is also balanced in terms of Membership
 * ustomers use the take away method more than others.
 * Monthly visitors tend to use the take away and dine in method.
 * Weekly visitors tend to use the take away method and most of them are loyal customers.
 * Price rate greatly affects customer loyalty or not, rates are associated with a higher price range, which indicates some customer dissatisfaction. so the importance of price rates and promotions for customers to attract interest and can be compared with other stores.

From these conclusions, several suggestions can be made, in a concise form, with the aim of inspiring some ideas to increase sales of Starbucks Malaysia:

* Given that most of the customers are young people, and also considering the fact that Sales and Promotion are very important to them, why not use more modern means of communication, such as Social Networks, and the like.
* most customers use drive thru or take away, whether it's best not to do food or beverage delivery services, or instant coffee products that are easy to find and don't need to visit the store.
* As we can see that a lot of customers use the drive thru or take away, why not provide more service for the dine-in to attract more people to stay.
* since the customers are mostly young, why not make a menu or meal suitable for an older customer.




