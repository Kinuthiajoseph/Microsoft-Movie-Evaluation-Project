# Microsoft-Movie-Phase1-Project
Author: Joseph Kinuthia Githinji

## Overview

The project aims to analyze the movie industry data to provide insights for Microsoft's movie analysis project. The business problem revolves around understanding the factors that contribute to the success of movies and identifying potential opportunities for Microsoft in the industry. The dataset includes information on movie titles, release years, genres, ratings, votes, studios, and domestic and foreign gross revenues. Various methods such as data visualization, correlation analysis, and studio performance evaluation are employed. The results highlight a weak positive correlation between average rating and domestic gross revenue, as well as a skew in the distribution of domestic gross revenue. Additionally, popular genres are identified, and the analysis reveals the top movie studios based on domestic gross revenue. Recommendations include focusing on genres with higher potential for revenue, optimizing movie runtimes, leveraging successful studios for partnerships or acquisitions, and considering market trends for strategic decision-making.

## Business Problem
The business problem we are trying to solve is to help Microsoft, who wants to create a new movie studio, to identify the types of films that are currently performing well at the box office. By understanding which types of films are currently successful, Microsoft can make data-driven decisions about what types of films to produce in order to maximize their chances of success.

To answer this question, we will be analyzing two datasets: "movie_basics" and "movie_ratings". From these datasets, we will try to answer questions such as:

* What are the most popular movie genres?
* Which movie genres have the highest average ratings?
* What is the relationship between movie budget and revenue?
* Which movie studios have produced the most successful films?
***

## Data Understanding

***
For this project, we are using two datasets: "movie_basics" and "movie_ratings".
***
The "movie_basics" dataset was obtained from the IMDb database and contains information about movies such as title, year of release, genre, and production studio. 
***
The "movie_ratings" dataset was also obtained from the IMDb database and contains information about the ratings and reviews of movies.
***
"""
These datasets relate to our data analysis questions because they provide information about movie genres, 
production studios, and ratings, which are all important factors to consider when deciding what types of films to produce.
Our target variable is the movie's revenue or box office gross, 
which is not available in these datasets but can be obtained from external sources such as the "bom.movie_gross.csv" dataset. 
We will use this dataset to merge with our "movie_basics" dataset and obtain revenue information for each movie.
The properties of the variables we intend to use include categorical variables 
such as movie genres, production studios, and directors, and continuous variables such as movie ratings, budget, and revenue. 
We will need to clean and preprocess the data in order to extract the relevant information and transform it into a usable format for analysis.
"""

# Methods
This project uses descriptive analysis, including description of trends using visualiuzation and data modelling. 

# Results
The scatter plot shows a weak positive correlation between the average rating and domestic gross revenue of movies. There is a skew or imbalance in the distribution of domestic gross revenue. This means that most of the movies have lower domestic gross revenue, while only a few movies have higher domestic gross revenue. 
The bar chart shows a decreasing trend in the number of movies released over the years, with a peak in 2011. This trend can be useful for businesses to understand the competition and market trends.
***
 The stacked bar chart shows that domestic revenue is consistently higher than foreign revenue. It also shows that there was a dip in revenue in 2012.
***
Histogram of runtime minutes: The histogram shows that the majority of movies have a runtime between 80 and 120 minutes, with a peak around 100 minutes.
***
Bar plot of genre distribution: The bar plot of genre distribution shows that the most popular genres of movies are Drama, Comedy, and Action. This can be useful for businesses to understand the preferences of their target audience.
***
The models fit the data well and provide useful insights for businesses. However, it is important to note that the results may not generalize beyond the data we have, as they are based on a specific dataset. Further analysis and testing may be required to validate the results.
***
Overall, the models can be useful for businesses to understand the trends and preferences of their target audience and make informed decisions regarding movie production and distribution.

## Conclusions
Overall, our analysis provides valuable insights into the movie industry. The business can use these insights to make data-driven decisions, such as identifying the most profitable genres and focusing on increasing foreign revenue.

However, there are limitations to our analysis. For example, we did not consider the impact of external factors such as competition and economic conditions on the movie industry. Also, the dataset is limited to a specific time frame and region, which may not be representative of the entire industry.

To improve this project in the future, we could consider including more data sources to increase the scope of our analysis. We could also use machine learning algorithms to predict the success of a movie based on its genre, runtime, and other factors.

## Recommendations

Based on the evaluation of the visualizations, here are some recommendations for the Microsoft Movie Analysis project:

Revenue Analysis: Explore the distribution of domestic and foreign gross revenue for movies. Analyze the factors that contribute to higher revenue, such as genre, studio, release year, and average rating. Identify genres or market trends that are more likely to generate higher revenue and provide insights on potential investment opportunities.

Genre Preferences: Investigate the popularity of different genres among the audience. Analyze the distribution of movies across genres and identify the most popular genres over time. This information can help Microsoft understand the preferences of their target audience and guide decision-making in movie production and acquisition.

Runtime Analysis: Examine the distribution of movie runtimes and identify patterns or trends. Determine the average or preferred runtime among viewers and analyze whether there is any correlation between runtime and average ratings or revenue. This analysis can help in optimizing movie lengths and catering to audience preferences.

Release Year Analysis: Study the trends in movie releases over the years. Identify periods of higher or lower movie production and analyze the factors that contribute to these trends. This analysis can assist in understanding the market competition and making strategic decisions on release timing.

Average Rating Analysis: Investigate the relationship between average ratings and other factors like revenue, genre, and runtime. Analyze whether higher ratings lead to higher revenue or popularity. Identify genres or attributes that tend to receive higher ratings and leverage this information for content selection and production decisions.

Competition Analysis: Explore the competitive landscape by analyzing the market share of different studios. Identify the major players in the industry and analyze their strategies for success. This analysis can provide insights into potential partnerships, acquisitions, or competitive strategies for Microsoft in the movie industry.


