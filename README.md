# Zomato Restaurant Clustering and Sentiment Analysis
Summary:

This project uses advanced data analytics to understand restaurants and customer feedback on Zomato, an online food delivery platform. The data includes essential restaurant details like name, location, cuisines, cost, ratings, and reviews. We clean and preprocess the data to make it suitable for analysis by removing duplicates and handling missing values.

Next, we apply clustering to group similar restaurants using the k-means algorithm. We consider features like location, cuisines, and cost, determining the optimal number of clusters using the elbow method.

Sentiment analysis on user reviews helps us understand overall sentiments. Reviews are classified as positive, negative, or neutral, and common words are visualized through word clouds.

The analysis reveals that city restaurants cluster into groups based on location, cuisines, and cost. Overall sentiment analysis indicates a positive customer sentiment.

This project shows the effectiveness of clustering and sentiment analysis in understanding Zomato's restaurant data, providing valuable insights for informed decision-making by restaurants and customers. Expanding the project to other cities or countries could offer insights into diverse eating habits and preferences.

Steps:
1)Dataset loading and cleanup
2)EDA
3)Feature Engineering: Creating new features, removing redundant ones.
4)Pre process: Feature scaling.
5)Finding ideal number of clusters: Elbow chart/ dendrogram.
6)Model Implementation and interpretation
The project deals with the ever-changing restaurant industry by using machine learning to group restaurants and analyze customer reviews. It aims to help restaurant owners understand customer expectations better. Analyzing Zomato data, including cuisine, costs, and reviews, the project wants to help customers find great local restaurants and assist the company in growing and improving. The goal is to use reviewer information to figure out sentiments. We want to provide helpful data-driven insights for customers and Zomato in navigating the restaurant scene.

Conclusion:
This Zomato restaurant clustering and metadata sentiment analysis project concludes that leveraging natural language processing and machine learning algorithms enables the creation of a model adept at accurately clustering restaurants based on reviews and sentiments. The project has proven instrumental in discerning customer preferences and understanding the profound impact of customer feedback on the restaurant industry.

We conducted clustering on restaurant data using cost, rating, and cuisines, employing dimensionality reduction techniques for 2D visualization. Following the elbow method and silhouette scores, KMeans clustering with k=4 emerged as the optimal choice.

Our clustering results revealed four distinct clusters of restaurants:

Premium Continental Restaurants
Local Street/Fast Food
International Cuisines
Cafe, Ice Creams and Desserts
Employing sentiment analysis facilitated the classification of review texts as positive or negative, offering a nuanced understanding of customer feedback and pinpointing areas for service improvement. Various feature engineering techniques were applied to extract sentiments, identifying key areas of enhancement based on negative reviews.

Taste
Price
Behaviour
hygiene
Quality
Service Time
Experience
In the future, we could look into creating a recommendation system based on what users like and rate highly. This project shows how combining data from different places and using various analysis methods can uncover useful information for Zomato and business owners.
