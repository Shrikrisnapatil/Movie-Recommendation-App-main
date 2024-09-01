![image](https://github.com/OdinMK12/Movie-Recommendation-App/assets/96242979/be160141-19b3-4f9c-aeee-2e9937548ed0)


# Movie-Recommendation-App
In this project I have built a movie recommender system. The algorithm recommends products that are similar to the ones that a user has liked in the past. This similarity (generally cosine similarity) is computed from the data we have about the items as well as the user’s past preferences.

![image](https://github.com/OdinMK12/Movie-Recommendation-App/assets/96242979/4c6a7c34-a8fc-44b1-9c8b-305053bac28c)


# How it does :
Content Based Filtering - They suggest similar items based on a particular item. This system uses item metadata, such as genre, director, description, actors, etc. for movies, to make these recommendations. The general idea behind these recommender systems is that if a person liked a particular item, he or she will also like an item that is similar to it.

# How to get the API key for images? :
Create an account in https://www.themoviedb.org/, click on the API link from the left hand sidebar in your account settings and fill all the details to apply for API key. If you are asked for the website URL, just give "NA" if you don't have one. You will see the API key in your API sidebar once your request is approved.

![image](https://github.com/OdinMK12/Movie-Recommendation-App/assets/96242979/42f2a0db-449d-43f2-99ef-bb921bee502d)

# Similarity Score :
How does it decide which item is most similar to the item user likes? Here we use the similarity scores.
It is a numerical value ranges between zero to one which helps to determine how much two items are similar to each other on a scale of zero to one. This similarity score is obtained measuring the similarity between the text details of both of the items. So, similarity score is the measure of similarity between given text details of two items. This can be done by cosine-similarity.

![image](https://github.com/OdinMK12/Movie-Recommendation-App/assets/96242979/5ae7c44f-bb0e-479e-b3c8-514475c3b1e5)

How Cosine Similarity works? :
Cosine similarity is a metric used to measure how similar the documents are irrespective of their size. Mathematically, it measures the cosine of the angle between two vectors projected in a multi-dimensional space. The cosine similarity is advantageous because even if the two similar documents are far apart by the Euclidean distance (due to the size of the document), chances are they may still be oriented closer together. The smaller the angle, higher the cosine similarity.

![image](https://github.com/OdinMK12/Movie-Recommendation-App/assets/96242979/3d9df13a-a4d8-4700-bcd8-d7bf4affc150)

# Sources of the datasets :
I have used the TMDB 5000 movies dataset to build the model

You can collect dataset from https://www.kaggle.com/tmdb/tmdb-movie-metadata
