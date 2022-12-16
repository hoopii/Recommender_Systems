# Recommendation Systems
### Build item-based, user-based and model-based recommender system based on movie ratings

![grafik](https://user-images.githubusercontent.com/100354393/205451966-2a04b46f-e4b4-4723-948f-564818cd25d5.png)
 
## Goal
Create user-based, item-based and model-based movie recommender systems as well as simple popularity rankings inspired by Netflix recommendations using a real life dataset of nearly 10.000 movies with more than 100.000 user ratings  

![grafik](../main/Screenshot-2022-01-28-101727.png)



## Dataset
- GroupLens, which gathered this data, is a research group in the Department of Computer Science and Engineering at the University of Minnesota. Since its inception in 1992, GroupLens's research projects have explored a variety of fields including:   
  - recommender systems  
  - online communities  
  -  mobile and ubiquitious technologies   
  -  digital libraries    
  -  local geographic information system   
- This and other GroupLens data sets are publicly available for download at http://grouplens.org/datasets/ 
- GroupLens Research operates a [movie recommender](http://movielens.org) based on collaborative filtering, MovieLens, which is the source of these data
- The dataset (ml-latest-small) describes 5-star rating and free-text tagging activity from [MovieLens](http://movielens.org), a movie recommendation service. 
-  It contains 100.836 ratings and 3683 tag applications across 9.742 movies.     
- These data were created by 610 users between March 29, 1996 and September 24, 2018. This dataset was generated on September 26, 2018.  
--> for more information on the dataset look at the [description file in the repository](../main/description_dataset.txt)  

## Skills/Methods
- Pivot-Tables in Python/Pandas
- Apply cosine_similarity function in Scikit-Learn
- Compute Cosine Similarities
- Compute weighted averages
- apply matrix factorization algorithms for model based recommenders
- 
- 

## Basic Steps 
Based on the example User-based Collaborative Filtering: 
1. Create a user-item matrix as data structure for further processing
2. Replace Missing Values
3. Compute Similarities between Users
4. Turn Similarities into Weights using the weighted average
5. Estimate missing Ratings
6. Create a function that takes the users userId, and a number (n) and outputs the n most recommended movies based on the cosine similarity of other users.
7. Evaluate the recommendation system

## Files in this repository
