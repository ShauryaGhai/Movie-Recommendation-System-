# Movie-Recommendation-System-
This project is a recommendation layer on top of OTT platforms that can make comprehensive moviie suggestions based on various paramters like genre , reviews, ratings, recommendations etc. It comsists of 3 recommender systems:
1)Populairty Based recommender systems-User will input a genre (g), minimum ratings threshold (t) for a movie and no. of recommendations(N) for which it should be recommended top N movies which are most popular within that genre(g) ordered by ratings in descending order where each movie has at least (t) reviews.
2)Content Based Recommender System -recommends top N movies based on similar movie(m) genres.
3)Collaborative Based Recommender System-Recommends top N movies based on K similar sers for a target user U.

The project was made using several libraries like Scikit-Learn,Scipy, Matplotlib,Seaborn, Pandas, and Numpy .After loading and pre processing the data, i undertook some exploratory data analysis using Seaborn and Matplotlib to visualize data distributions, such as the number of ratings per movie or per user.Algorithms like NearestNeighbors from Scikit-Learn were used to find similar movies or users based on ratings.Finally recommendations were generated and ipywidgets was used for a graphical representation of the work .
