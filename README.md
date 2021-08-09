# Zomato-Restaurant-Rate-Prediction
------------------------------------------------------------------------------------------------------

![zomato-1200x600](https://user-images.githubusercontent.com/76476273/128660287-c9bc546d-21bf-426f-af25-df6889ba6052.jpg)


# Problem Description 
--------------------------------------------------------------------------------------------------------
Restaurants from all over the world can be found here in Bengaluru. From United States to Japan, Russia to Antarctica, you get all type of cuisines here. Delivery, Dine-out, Pubs, Bars, Drinks,Buffet, Desserts you name it and Bengaluru has it. Bengaluru is best place for foodies. The number of restaurant are increasing day by day. Currently which stands at approximately 12,000 restaurants. With such an high number of restaurants. This industry hasn't been saturated yet. And new restaurants are opening every day. However it has become difficult for them to compete with already established restaurants. The key issues that continue to pose a challenge to them include high real estate costs, rising food costs, shortage of quality manpower, fragmented supply chain and over-licensing. This Zomato data aims at analysing demography of the location. Most importantly it will help new restaurants in deciding their theme, menus, cuisine, cost etc for a particular location. It also aims at finding similarity between neighborhoods of Bengaluru on the basis of food.

* Does demography of area matters?
* Does location of particular type of restraurant depends on people living in that area>
* Does theme of restraurant matters?
* Is food chain category restraurant likely to have more customers than its counter part?
* Are any neighbourhood on similar based on the type of food?
* Is particular neighbours is famous for itw own kind of food?
* If two neighbours are similar does that mean these are related or particular group of people live in neighbourhood or these are places to eat.
* What kind of food is famous in locality.
* Do entire locality loves veg food, if yes then locality populated by particular set of people eg Jain, Gujarati,Marwadi who are basically veg.

# Problem Statement 
--------------------------------------------------------------------------------------------------------------------
The Main Goal Of This Project Is To Perform Extensive Exploratory Data Analysis(EDA) On The Zomato Dataset And Build An Appropriate Machine Learning Model That Will Help Various Zomato Restaurants To Predict The Cost Of Restaurant For Two People Based On The Given Indicators In The Training Data.  

# Architecture 
-----------------------------------------------------------------------------------------------------------------------
![image](https://user-images.githubusercontent.com/76476273/128660428-15952aaf-8958-484b-a243-b8f7345b8b17.png)


# Data Description
-----------------------------------------------------------------------------------------------------------------------
This dataset predicts the visibility distance based on the different indicators as below:

1.	serial: The index/serial number
2.	URL : The URL for the restaurant 
4.	address:  The address of the restaurant.
5.	name: The name of the restaurant.
6.	online_order: Does the restaurant allow online order(Yes/No)
7.	book_table: Does the restaurant allow table booking(Yes/No)
8.	rate: Restaurant rating out of 5.
9.	votes: The number of votes for the restaurant.
10.	Phone: Resyaurant contact number
11.	Location: Location of the restaurant
12.	rest_type:Type of the restaurant(Casual Dining, Café etc.).
13.	dish_liked: The Most liked dishes in the restaurant(Pasta, Lunch Buffet, Masala Papad etc.)
14.	cuisines: North Indian, Mughlai, Chinese etc.
15.	approx_cost(for two people): In Rupees. (target Column)
16.	reviews_list: The List of reviews
17.	menu_item: Open Dosa', 'Benne Set Dosa' etc.
18.	listed_in(type): Buffet, café etc
19.	listed_in(city): The part of city where restaurant is listed.

# Tools And Libraries Used 
----------------------------------------------------------------------------------------------------------------------------------------------------

* Flask is for creating the application server and pages.
* matplotlib , seaborn , plotly are used for data Visualization 
* numpy is for arrays computations and mathematical operations 
* pandas is for Manipulation and wrangling structured data
* scikit-learn is used for machine learning tool kit
* pickle is used for saving model
* SQLite is for database operation
* josn is for data validation processes
* os is used for creating  and deleting folders
* csv is used for creating .csv format file

# Algorithms Used
-----------------------------------------------------------------------------------------------------------------------------------

*  KMeans Clustering Algorithm
*  Decision Tree Regress
*  XGBoost regressor
*  GridSearch CV 
