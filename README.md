# Amazon-Apparel-Recommendation-System
As you can see the system is quite accurately giving us the product recommendation. I think the BOW model is giving us quite a good variety of products and also displaying different types of brands. In tfidf model, the products are quite restricted to being similar and of the same brand but BOW is giving us a better variety since it is changing the brands.

In this notebook we learned,

Basic data statistics.

How to build an easy recommendation system using BOW and TF-IDF.

Visualized the results with heatmaps and images from json files.

Used cosine similarity and pairwise distances as metrics to evaluate product similarity.

Due to time constraints and an easy to use application, I used only around 16k data points, if you have time to spare you can get even better results by not dropping the null values. On the other hand, removing duplicates was quite important as in the last fewer words the only thing irrelavant was the size of the apparel, it is pretty obvious the customer doesn't want to see the exact same product with only a change in the size, hence removing it was a must.


