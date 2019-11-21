# Personalized Recommender System

## Motivation <br/>
The ratings and reviews for a product given by a user does not always reflect the true scenario. There may be cases wherein the user simply chooses to rate all items equally, or cases wherein the customer didn’t like a product and gives harsh comments which may not align with the given rating. To understand such a problem and dig deeper, we have chosen Epinion dataset. This is a who-trust-whom online social network of a general consumer review site Epinions.com. Apart from providing reviews and ratings for products, members of this site can also build trust relationships with other users. 

## Objective <br/>
Epinion consumer review dataset fit well for the recommendation system use-case. The trust data information partially alleviates the problems like cold-start, long-tailed datasets etc by leveraging information from trusted users. Trust based relationships between users can be calculated both explicitly and implicitly. Implicit Trust based recommendation systems are useful when the explicit trust relationships are not provided. Also, a given rating might not be the true measure if the review comments do not align with it. Sentiment analysis can be performed on the review comments to confirm the correctness of the given ratings.

The focus of this project are on three different aspects in which the dataset can be analyzed and processed:

### Sentiment analysis of product reviews <br/>
A given rating might not be the true measure if the review comments do not align with it. Many a times the reviews reflect the true intent of the user which may not align with the rating.
These reviews can be utilized for sentiment analysis to deduce true rating of a product.
The overall sentiment is often inferred as positive, negative, or neutral from the value of the polarity score. 

### Implicit Trust based recommendation system <br/>
Using Trust relationships to predict the item ratings can improve the prediction accuracy.
Trust based relationships between users can be calculated both explicitly and implicitly. Explicit Trust based relationships depends on the type of system. In a social network settings, trust between two users are provided in the dataset. However, sometimes trust between users are not evident in the data so the behaviour between two users can hint information about their trust relationship. Implicit Trust based recommendation systems are useful when the explicit trust relationships are not provided.
One advantage of Implicit Trust based recommendation systems is that they are generalizable across datasets. 

### Graph-based Trust network relationship <br/>
The trust-based connections can be utilised to form a user-network and different centrality measures such as degree, closeness and betweenness can be measured to identify important/most popular users.
Trust scores can be calculated to gauge most trusted users.
Trust based networks can be utilized for recommendations assuming that users’ preferences should be similar to those in their trusted network.
