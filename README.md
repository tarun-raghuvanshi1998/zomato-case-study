# zomato-case-study
#Exploratory Data Analysis of Zomato Bangalore Restaurants

#Introduction

With the rise of meal delivery services, everyone can now enjoy their favorite restaurant food from the comfort of their own home. Giant food aggregators and food shipping companies like Zomato have made it feasible. Zomato is one of India’s most extensively used services for searching restaurants, ordering food online, making table reservations, etc. Bangalore, home to many restaurants and cuisines worldwide, has over 51,000 restaurants doing their business through systems like Zomato. This wide variety is exponentially increasing each day.

The goal of this article and its content is to comprehend the factors that influence the establishment of restaurants in various locations throughout Bangalore; these factors include aggregate consumer score, cuisines offered, type of service provided, and numerous others. With increasingly more eating places, it’s becoming harder for restaurants to run successfully, particularly in a metropolitan metropolis like Bangalore. By studying the Zomato dataset, you can get deeper insights into some of the influencing factors that improve the functioning of a restaurant in Bangalore.

Today, we will investigate a dataset that carries approximate facts about the restaurant chains in Bangalore that also run on Zomato.

#A description of the dataset:

The dataset has been taken from Kaggle. It contains around 51717 rows and 17 columns of data. The attributes in the dataset are as follows:

1.URL: The restaurant’s website URL
2.address: Address of the restaurant
3.name: Name of the restaurant
4.online_orders: It specifies if the restaurant takes online orders or not.
5.book_table: Indicates whether or not the restaurant offers table reservations.
6.rate: The restaurant’s rating out of 5
7.votes: Number of votes received by the restaurant on Zomato
8.phone: the restaurant’s phone number
9.location: the neighborhood in which the restaurant is located.
10.rest_type: specifies the type of restaurant.
11.disk_liked: Indicates which dishes were popular among customers in that restaurant.
12.Cuisines: Cuisines available at the restaurant
13.approx_cost (for two people): Estimated cost of food in that restaurant for two people.
14.Reviews_list: Reviews given by users
15.menu_item: The restaurant’s menu
16.listed_in(type): Specifies the type of service provided by a restaurant
17.listed_in(city): The restaurant is on the city’s list.


#Objectives
The analysis that we are going to perform shall answer the following questions:

1.How many restaurants in Bangalore take online orders?
2.What percentage of restaurants offer table booking facilities?
3.What was the most common rating received by restaurants?
4.Is there any correlation between the approximated cost for two people and the ratings of a restaurant?
5.The top five cities in Bangalore with the highest and lowest-rated restaurants.
6.Which cuisine do customers like the most?
7.What is the average price for two people, based on the type of service?
8.Does the restaurant’s rating depend on whether it accepts online orders?
9.What are the top 10 highest-rated restaurants?
10.What was the most common rating?
11.Top 10 rating of resturant those have northindian food
12.Top 10 cheapest rating resturant those have northindian food
13.How many resturant have afghan chicken food?
14.How many resturant in bhanshankari
15.Is there any difference between votes of restaurants and accepting and not accepting online orders?
