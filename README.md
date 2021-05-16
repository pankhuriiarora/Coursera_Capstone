# Restaurant Guide
This repository is a model which suggests Restaurants in Delhi on the basis of cuisine, area and rating. This model uses Kaggel data analyze it and suggests the best pick according to the model. In the model a user can see restaurant's geographic details on a map which is built using folium library.

After cleaning the data and bringing it to the required form, k-mean clustering is used to form groups of restaurants. To get the optimal K-mean, k-mean elbow method is used. Foursqaure API is used to fetch necessary details like reviews and ratings.
