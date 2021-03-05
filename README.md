# Anime-Recommendation-System

### Kaggle Dataset:
This is a kaggle Dataset.
Source - https://www.kaggle.com/CooperUnion/anime-recommendations-database


### Objective:
In the notebook we will build a basic anime collaborative recommendation system. First of all let's have a look at the dataset.

### Dataset Info:
This data set contains information on user preference data from 73,516 users on 12,294 anime. Each user is able to add anime to their completed list and give it a rating and this data set is a compilation of those ratings. Its composition in numbers:

20.000.000 ratings
460.000 tags
27.000 movies

### Content:
#### Anime.csv that contains ratings of movies by users:

anime_id - myanimelist.net's unique id identifying an anime.
name - full name of anime.
genre - comma separated list of genres for this anime.
type - movie, TV, OVA, etc.
episodes - how many episodes in this show. (1 if movie).
rating - average rating out of 10 for this anime.
members - number of community members that are in this anime's "group".

#### Rating.csv that contains movie information:

user_id - non identifiable randomly generated user id.
anime_id - the anime that this user has rated.
rating - rating out of 10 this user has assigned (-1 if the user watched it but didn't assign a rating).

### Dependencies:
pandas 
numpy
seaborn
matplotlib
