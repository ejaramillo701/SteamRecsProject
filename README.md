# SteamRecsProject
Final Project for Stat208

A recommender system is a model that seeks to predict the preferences a user would give to a collection of items. Today recommender systems form the basis of the targeted advertisements and product suggestions we see throughout commercial industry. Broadly speaking, recommender systems fall into three major classes: content-based filtering, collaborative filtering, and novel hybrid methods. Content-based filtering involves creating "profiles" of different classes of items and recommending users items that fall into the same or similar profiles to items they have already rated. Menawhile, collaborative filtering involves identifying similar users based upon known common ratings, then recommending items to a target user based on what other similar users have rated highly. 

Both methods can be implemented using a variety of approaches and algorithms. Content-based filtering is often implemented via k-means clustering, bayesian classifiers, decision trees, and artificial neural networks. Collaborative filtering is often implement via nearest-neighbor algorithms or by latent factor models that rely on matrix factorization. 

For this project, I will be studying several of these models and applying them to the Steam dataset collected by O'Neill, Vazirpour, Wu, and Zappala (available here: https://steam.internet.byu.edu/). Steam is a videogame distribution service and gaming network with hundreds of millions of users and roughly 34,000 games available on the platform. This dataset, collected in 2015, should provide a perfect testing ground for these different models. In particular, the sparsity and scale of the data will provide a challenge similar to wwhat data scientists in industry often have to face. 

At the moment, I am using the following articles/books as a basis for my reading:

[1] "Matrix Factorization Techniques for Recommender Systems" by Bell, Koren, Volinsky (2009)

[2] "Recommender Systems: The Textbook" by Aggarwal (2016)

[3] "Building a Recommendation System in TensorFlow: Overview" (https://cloud.google.com/solutions/machine-learning/recommendation-system-tensorflow-overview)

Wherever possible I plan to use existing software libraries that have implementations of many of the necessary algorithms. This is done not only out of convenience but also out of necessity since analyzing a dataset of this size will require highly optimized implementations of these algorithms.
