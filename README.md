#Team Phoenix
<h3>Dataset :https://www.kaggle.com/datasets/grouplens/movielens-20m-dataset?resource=downloa </h3>
-This Repository contains analysis of MovieLens20 Dataset from kaggle. The dataset is intended for use in Data Visulization through EDA, data preprocessing, matrix factorization, and K-nearest neighbours.
- There are 6 csv(Comma Seprated Files) files attached to the dataset.
The data Description is as follows:

**genome_scores** contains following columns:
-movieId
-tagId
-relevance
**genome_tag** contains following columns:
-tagId
-tag
**link** contains following columns:
-movieId
-imdbId
-tmbdId
**movie** contains following columns:
-movieId
-imdbId
-tmbdId
**rating** contains following columns:
-userId
-movieId
-rating
-timestamp
**tag** contains following columns:
-userId
-movieId
-tag
-timestamp
 
<h2>EDA :</h2>
-Exploratory Data Analysis (EDA) was performed to gain insights into movies, ratings,genres aand other categories.
In EDA we provide data  visualisation in different graph method like density plot, horizontal bar chart,vertical bar chart, column chart, etc. EDA summarize the main behaviour, features, and patterns in a dataset.

<h2>Data Preprocessing :</h2>
-Data preprocessing and transformation involve cleaning, organizing, and structuring raw data to make it suitable for analysis or model training.
Data preprocessing is the initial step in data preparation, where the raw data is cleaned and prepared for further analysis. We used the metadata and the content column as our corpus and did our preprocessing on it. We make use of stemming/lemmetization, tokenization, removal of stopwords in the process.
The data cleaning was also done based on our requirement for the project that was about content based filtering. 
Since our data was from kaggle, we did not have to perform a lot of preprocessing on it. The main part was to identify useful datasets and columns that will be giving us fruitful results.

<h2>Collaborative Filtering :</h2>
-Collaborative Filtering recommends items based on similarity measures between users and/or items. The basic assumption behind the algorithm is that users with similar interests have common preferences.
In Collaborative Filtering, we tend to find similar users and recommend what similar users like. In this type of recommendation system, we don’t use the features of the item to recommend it, rather we classify the users into clusters of similar types and recommend each user according to the preference of its cluster.

There are basically four types of algorithms o say techniques to build Collaborative filtering based recommender systems:

-Memory-Based
-Model-Based
-Hybrid
-Deep Learning

 <h2>Classification model building and Model evaluation : </h2>
		Building a classification model involves several key steps, such as model selection and evalution.
  -We have used the K-Nearest neighbour algorithms, and matrix factorisations, to give the best recommendations to the user.
 - The KNN algorithm finds the nearest neighbors for that movie, based on the cosine similarity and gives most similar predictions to the user.
 - The rating data is a large of 20 M size. Also, the user-movie matrix is a spares matrix. So, we have used the matrix factorization method to predict the recommendations to the user.

<h2> Contributors ✨ </h2>
<table>
    <tbody>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/KrishRupapara"><img src="https://avatars.githubusercontent.com/u/94665286?v=4" width="100px;" alt="KrishRupapara"/><br /><sub><b>KrishRupapara</b></sub></a><br /></td>  
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/kir1906"><img src="https://avatars.githubusercontent.com/u/137956777?v=4" width="100px;" alt="kir1906"/><br /><sub><b>kir1906</b></sub></a><br /></td> 
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/asma-2922"><img src="https://avatars.githubusercontent.com/u/137956777?v=4" width="100px;" alt=""/><br /><sub><b>asma-2922</b></sub></a><br /></td>    
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/preyali"><img src="https://avatars.githubusercontent.com/u/137956777?v=4" width="100px;" alt=""/><br /><sub><b>preyali</b></sub></a><br /></td>    
  </tbody>
</table> 


