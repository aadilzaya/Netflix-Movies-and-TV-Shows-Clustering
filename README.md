# Netflix-Movies-and-TV-Shows-Clustering

The project's objective involves clustering Netflix shows and movies to create groups based on shared characteristics, enhancing the platform's recommendation system. This facilitates the delivery of personalized movie and TV show recommendations by leveraging user behavior, preferences, and viewing history.

# Objective

The objective is to group Netflix shows into different clusters so that shows with similar specifications lies in one group.

# Project Workflow

1.Getting to know your data: Investigate and gain insights into the dataset.
2.Exploratory data analysis (EDA): Recognize patterns and derive conclusions.
3.Data cleaning: Scrutinize for duplicates, handle missing values, and tackle outliers.
4.Textual data preprocessing: Eliminate stopwords and punctuation, convert text to lowercase, and transform it into word vectors.
5.Cluster implementation: Utilize k-means and hierarchical clustering to categorize shows.
6.Content-based recommendation system: Offer 10 recommendations based on the shows you've recently viewed.

# Conclusion

- The dataset consists of 7787 records and 11 columns.
- Our initial steps involved cleaning and conducting exploratory data analysis (EDA) on the dataset.
- We observed that Netflix predominantly produces more movies than TV shows, and the number of shows is rapidly increasing.
- The United States boasts the highest number of shows within the dataset.
- Starting from 2015, TV shows have gained significant prominence on Netflix.
- We selected specific attributes, namely cast, country, genre, director, rating, and description, for clustering the data.
- To address dimensionality reduction, we employed principal component analysis (PCA).
- In the context of K-means clustering, we identified an optimal cluster count of 6, utilizing both the elbow and silhouette methods.
- In the agglomerative clustering algorithm, we determined that the ideal number of clusters is 7.
- A content-based recommender system was established using cosine similarity, which provides 10 recommendations based on the user's recent viewing history.
