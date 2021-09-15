# Project Title

Movie Recommendation System 


## Description

In this project I created a recommendation system specifically for films. Which provides recommendations based on the similarity of content from movies that users have watched before.


## Step By Step Create Movie Recomendation System 

### 1. Create Stopwords 

I use the bag of words to get the words that occur most often. I choose the 500 most frequently occurring words and then I selected the most frequently occurring words and not keywords.

### 2. Features Extraction 

I use tfidf to perform feature extraction on metadata which contains genre, cast, keyword, director, title and overview. I will save the results from tfidf. 

### 3. Document Similarity with Cosine Similarity 

I used cosine similarity to find the similarities between the metadata and 10 metadata of the most similar films would be recommended to users.

### 4. ML Engineering 

At this stage I wrapped all the programs for the recommender system so that it would be easier to use. As can be seen below an example of aladin film:

![result](https://github.com/AfrizalSeptiansyah/Recommendation-System/blob/main/asset/recommender.PNG?raw=true)

# Conclusion 
So far, we have succeeded in prototyping the recommendation system, please give it a try.

Thank you for reading :) 
