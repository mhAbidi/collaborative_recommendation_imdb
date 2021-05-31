# collaborative_recommendation_imdb

This is a training project to demonstrate the use of collaborative filter in a real world application.


Here we will be working on IMDB movie ratings dataset.

The goal over here is to create an algorithm which can easily and precisely predict which movie the user will enjoy and which movies the user will hate.

Collaborative filtering uses similarities between users and items simultaneously to provide recommendations. This allows for serendipitous recommendations; that is, collaborative filtering models can recommend an item to user A based on the interests of a similar user B. Furthermore, the embeddings can be learned automatically, without relying on hand-engineering of features.

### Check Jupyter Notebook for code and description.

#### Dataset used for this project:

Movies with Genre and user ratings. 

Source: https://drive.google.com/file/d/1WWQCl9w52M1sXNWd4JSKL7q-HHywk03p/view
<br>



### Approaches To CF:

#### 1. Cosine Similarity
collaborative_recommendation.ipynb <br>
Takes the user interests from  their historic ratings, and similarity with other users; using the cosine similarity;
then removes the items which the user has already seen; and recommends the items from the  library in order of 
perceived preference. 


#### 2. Dot-Product Similarity

#### 3. Euclidian Distance
 
 
