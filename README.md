# anime_recommendation_system
An Anime recommendation system built using Unsupervised Learning (Nearest Neighbors) which recommends 5 closest anime to an anime the user likes

------------------------------------------------

This is made using a Dataset from kaggle 

Link of dataset : https://www.kaggle.com/CooperUnion/anime-recommendations-database

This dataset is made from myanimelist.net which is a website which contains an anime and manga database and you can provide ratings keep track and view what anime you could watch next.

------------------------------------------------

It recommends the user 5 animes based on an anime the user likes.

It also recommends hentais.

The features considered while creating this model are : 

1. Genre (Slice of Life / Sport / Action / Drama etc. )
2. Type  (OVA / TV / Movie etc.)
3. Members (The number of members that are there on myanimelist.net of the particular show)
4. Rating (Rating is from myanimelist.net which has a public rated system and the ratings there are exceptionally accurate)
5 Episodes ( number of episodes in the show)

------------------------------------------------

The reason why episodes are considered while creating this model is because of the fact the many people like big animes (around 500 eps ) some like around (50 eps) and some like really short ones (12 eps). So episodes is also a major factor that needs to be considered.

------------------------------------------------