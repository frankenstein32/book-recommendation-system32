# book-recommendation-system32

### INTRODUCTION
The book recommendation system would help the user purchase a book, by recommending books based on collaborative filtering and association rule mining.

### PROBLEM STATEMENT
A recommendation system will help users who do not have enough individual knowledge to peruse through the different types of options offered by a website. It will provide the users with information to assist them to make a decision as to which items to purchase. The proposed work alters from the existing recommendation systems since the existing ones only consider one technique to recommend items to the users. They do not recommend items using two or more techniques and are not a Hybrid Recommendation System. The proposed system uses a combination of Collaborative Filtering and Association Rule Mining. Collaborative Filtering is used to predict the ratings of a particular item by calculating ratings given to similar items or ratings given by similar users. Association Rule Mining is used to extract different patterns and correlations between different items. Thus, the usage of both these techniques can help to control the data sparsity problem and cold start problem in recommendation systems.

### PROBLEMS
Problems faced by recommender systems:-  

- __Data Sparsity__: Data sparsity arises from the phenomenon that users in general rate only a limited number of items. 

- __Cold Start__: Personalized recommender systems take advantage of users’ past history to make predictions. The cold start problem apprehends personalized recommendations for customers with zero or negligible past history. 

- __Gray Sheep__: The collaborative filtering (CF) approach in recommender systems assumes that users' preferences are consistent among users. It is presumed that few of these consumers belong to a minor community of users who have uncommon likings, such users are incompliant with the CF fundamental hypothesis. They are grey sheep users. 

- __Shilling Attacks__: Recommender systems which are based on collaborative filtering are vulnerable to “shilling attacks” due to their open nature. Shiller’s inject a few unscrupulous “shilling profiles” into the database of ratings for altering the system's recommendation, due to which some inappropriate items are recommended by the system. E. Scalability Recommender 

### DATASET [<a href="https://drive.google.com/drive/folders/1Q9LuxgGISQC0PjzKW-5wt3vb6lVQ775X?usp=sharing">Link</a>]
The Book-Crossing dataset comprises 3 tables.

- __BX-Users__: It contains the users. Note that user IDs (`User-ID`) have been anonymized and map to integers. Demographic data is provided (`Location`, `Age`) if available. Otherwise, these fields contain NULL-values.
- __BX-Books__: The books are identified by their respective ISBN. Invalid ISBNs have already been removed from the dataset. Moreover, some content-based information is given (`Book-Title`, `Book-Author`, `Year-Of-Publication`, `Publisher`), obtained from Amazon Web Services. Note that incase of several authors, only the first is provided. URLs linking to cover images are also given, appearing in three different flavours (`Image-URL-S`, `Image-URL-M`, `Image-URL-L`), i.e., small, medium, large. These URLs point to the Amazon web site.
- __BX-Book-Ratings__: It contains the book rating information. Ratings (`Book-Rating`) are either explicit, expressed on a scale from 1-10 (higher values denoting higher appreciation), or implicit, expressed by 0.

### CONCLUSION
The escalating demands of Online Data have led to the invention of new techniques for presenting or rather recommending different products to users. This project will use both Collaborative filtering as well as Association Rule Mining in order to recommend different types of books to the users. Both these techniques will make a good Hybrid Recommendation System and also get rid of the Data Sparsity and Cold Start problem. Finally, the calculations of both algorithms will be checked corresponding to the individual results given by each collaborative method in order to validate this Hybrid-method.

__To be continued.....__ 😋✌🏻
