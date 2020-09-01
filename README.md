# Topic

Analyze data on Kaggle (https://www.kaggle.com/airbnb/seattle/data) to get the factors affect price and availability of lisitings in Seattle on AirBNB

# Libraries used:

Numpy
Pandas


# Motivation for the project:

I use this project to sharpen my data analysis skills and get familiar with numpy and pandas. In addition, I wants to analyze the data of those listings to come up with effective business strategies to increase both the booking rate and the profits. Therefore, I decide the analyze what factors is related to availability and price to see if there are something interesting. Finally, I will use the results to provide some suggestion to increase booking rate.

# Files in the repository:

In the calendar.csv, I get the everyday availability and price for 3818 listings in 2016. 
In Listings.csv, I get the 92 features for each listings, such as: bedrooms, zipcode, url, country…… .
In Reviews.csv, I get the reviews for those listings, including comments, date, reviewer….

# Summary of the results:

From the table and figure above, the busiest week in the year is 
2016/3/21–2016/3/27
2016/6/13–2016/6/26
2017/1/2

The available rate decreases by more than 2% within those periods. However, the price doesn't have the same trend as the available rate. From June to August, the price is the highest but the availability is relatively low. We can say that the demand is larger during the summer.

On Fridays and Saturdays, the average price is 5% higher than the other dates of the week and the availability is 0.5% lower than the other dates of the week. The reason is that people usually take trips on long weekends by taking one day off on Thurdays.  Therefore, the availability is going down from Thursday to Saturday and jump up on Sunday. It indicates that people prefer to travel from Thursday-Sunday than Friday-Monday, even though they are both a 3-day stay.

We know from the above figures that zip code does affect the price and availability. However, the price and the availability of different zip codes are not correlated. For the three zip codes below, price and availability are positively/negatively correlated.
98146(-0.33) negatively correlated
98134(0.34) and 98178(0.59) positively correlated

The higher the reviews_per_month, the lower the price, which makes sense as it means the room is more affordable. Other factors are also reasonable: larger rooms, more beds, rooms, bathrooms, and guests included.

We can do some promotion by those factors correlated to price and availability. For example, the price of zipcode 98178(0.59) is positively correlated to availability. AirBNB can provide some discounts for this area to see if the booking rate will increase. In addition, AirBNB can do some marketing to attract people to extend their stays to Sunday, which might increase the booking rate on Sundays.

