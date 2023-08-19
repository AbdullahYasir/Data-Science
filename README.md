# Finding Best Neighborhood to Live in Scarborough, Toronto

## A. Introduction
Canada is one of the world's best place to live in. People from all over the world move to Canada to live a better life. One of the main reasons people prefer to move to Canada is because of the quality of life provided by Canada including all the great facilities provided by them. When people travel to Canada then they need to do a lot of research in order to find the best city or neighborhood in which they can live. This requires a lot research that includes which neighborhoods has best and closest educational institutes, hospitals, grocery shops, malls, coffee shops, theaters and like minded people. One of the most important thing that people look for when moving to a new neighborhood is the housing prices of that neighborhood. They need to compare housing prices of the different neighborhoods In order to find the best housing prices in the best neighborhood. One of the most preferable place to live in Canada is Scarborough, Toronto.

To solve this problem, this project aims to create a comparative analysis of different neighborhoods in Scarborough, Toronto for the people who are looking for the suitable neighborhood for them. This includes the analysis of different features of neighborhoods that includes which neighborhoods has best housing prices, good schools according to their ratings, crime rate in the neighborhood, road connectivity, weather conditions and hospitals in the neighborhood. Hence, this project will help people to create awareness of the town before moving to it and will help them find the best neighborhood for them.

The goal of this project is to facilitate the people who are moving to Canada to start a fresh life. So, our target audience is the people that wanted to move to Canada to have a better life and are looking for the best suitable neighborhood according to their needs.

## B. Data Description
Scarborough Dataset
We will use combination of different datasets. First of all we need Scarborough dataset because we are trying to find the best neighborhood in Scarborough, Toronto. This dataset is not readily available and we cannot directly download it. To have this dataset, we need to scrap the web page of Wikipedia and then we will separate the table in that web page and will use it as our dataset. This dataset will contain postal codes, borough and neighborhoods in Scarborough, Toronto. [1]

Foursquare API Data
After having the dataset of different neighborhoods in Scarborough, we need to compare these neighborhoods. For this comparison, we require different features of these neighborhoods. These features includes all kinds of venues within the area of interest. These venues includes parks, hospitals, coffee shops, malls, grocery shops etc. To have this kind of information around the are of interest, we will use Foursquare Location Data that is one of the most popular location data provider whose data is used by top companies like Samsung, Snap chat, Twitter, Apple Maps etc. Foursquare API data will provide us the information about all the venues in neighborhoods. This information include venue name, location, photos, tip/reviews and rating of the venue. All these information about venue will help us in comparative analysis between different neighborhoods in Scarborough and will help us decide which neighborhood is the best.

We need to gather the information about venues near the neighborhoods in our Scarborough dataset. The radius that we will use for venues in neighborhood will be of 100 meters. We need to connect to Foursquare API and need to gather the information within the specific Latitude and Longitude provided by the postal codes in Scarborough dateset. The data that will be retrieved from Foursquare API will consist of following fields. [2]

Neighborhood
Neighborhood Latitude
Neighborhood Longitude
Venue
Name of the venue e.g. the name of a store or restaurant
Venue Latitude
Venue Longitude
Venue Category
## C. Methodology
K-Means Clustering
As we are looking to find the best neighborhood in Scarborough therefore, the technique we will use is clustering. We will compare it with big cities like New York and Toronto and need to find similar neighborhoods like these big cities that also have good quality of life. We will explore the neighborhoods in Scarborough, will segment them and will group them into clusters to find the similar neighborhood like New York and Toronto. we will cluster the data by using k-means clustering. K-Means clustering is the unsupervised learning type of machine learning algorithm that we will use to solve our problem.

Most Common Venues Near Each Neighborhood
No alt text provided for this image
## D. Results
Clusters in Scarborough
By using the k-means clustering approach on our dataset we developed different clusters of different neighborhoods in Scarborough depending upon the similarity in the clusters. The similarity was found using any Euclidean distance metric. Clusters are shown on the map of Scarborough in the figure below.

No alt text provided for this image
Average Housing Prices By Clusters in Scarborough
After making the clusters in Scarborough, we found the average housing prices in each cluster. This housing prices was retrieved by Foursquare API data corresponding to each cluster of neighborhood. A graph is shown below that compares average housing prices by clusters in Scarborough.

No alt text provided for this image
Top School Ratings By Clusters in Scarborough
We used the Foursquare API data to retrieve the school rating of each neighborhood and after developing clusters we find top school ratings by each cluster in Scarborough. A graph is shown below that shows a comparative analysis of top school ratings by clusters in Scarborough.

No alt text provided for this image
## E. Discussion
As Canada is one of the most popular destinations for people to move in because of the quality of life in Canada. We tried to solve this problem to help people moving to Canada find a better neighborhood. There could be many factors that influence people when deciding a new neighborhood to live in for a fresh start. Out of all these factors we considered two most important factors that a person looks for while finding a new neighborhood. These 2 factors are as follows.

Average Housing Prices in Neighborhood.
Top School Ratings in Neighborhood.
These 2 factors are the most important and everyone wants a neighborhood that has low housing prices and good school ratings. Everyone wants such housing prices that suits their budget and want to have good rating schools in neighborhood to have better education for their children. To solve these two problems we created a comparative analysis feature that compares the average housing prices and Top school ratings in all the neighborhoods in Scarborough. So, if a person wants to move to Scarborough, he can check this comparison and can find the best neighborhood in Scarborough according to their needs.

## F. Conclusion
In this project, the battle of neighborhoods, we aim to find the best neighborhood to live in. As Canada is one of the top destinations for the immigrants to live in therefore we considered Scarborough, Toronto as our target place that is one of the most popular places in Canada to move in for all kinds of people having different backgrounds and religions. We used k-means clustering approach to make the clusters of 103 different location in Scarborough and then find the similarity with the top cities like New York. After making the clusters of neighborhoods our goal was to find the best neighborhood. For that we developed 2 bar charts that shows the average housing prices and top school ratings in each clusters. With the help of these charts, immigrants can find the best neighborhood for them.

This project really helped me learn the complete data science cycle. From defining the business problem to the target audience, from data collection to data preparation, from methodology used for the project to the results obtained from the project, from discussion on results obtained to the conclusion, this capstone project has really helped me understand the complete cycle and has helped me learn how the data science problems are solved in real world. Moreover, with the help of this project i have learned how to use different data science tools and libraries such as pandas, numpy, scikit-learn, folium, beautiful soup, requests, json, xml and matplotlib to solve real world problems.

Future Work
I tend to improve my results in future. For now i have only considered two factors in deciding the best neighborhood i.e average housing prices and top school ratings. In future, i will increase diversity in my project and will include many other factors that influence the immigrants while deciding their new neighborhood. I will include top hospitals nearby, grocery stores, weather conditions, malls nearby, theaters nearby, restaurants and many more. By including all these factors, i will develop a more diverse and accurate tool for immigrants to decide their best neighborhood.

## G. References
[1] Scarborough, Toronto Dataset - Wikipedia

[2] Foursquare API
