# Book_Recommendation_Unsupervised
Unsupervised ML project with collaborative and content based filtering 

**OBJECTIVE :**

The main objective is to create a machine learning model to recommend relevant books to users based on popularity and user interests.
In addition to the ML Model prediction, we also have taken into account the book recommendation for a totally new user.

**INTRODUCTION:**

Recommender systems are today unavoidable in our daily online journeys.In a very general way, recommender systems are algorithms aimed at suggesting relevant items to users (items being movies to watch, text to read, products to buy, or anything else depending on industries).
Since, here I am trying to recommend books to users based on their past purchases or ratings the user gave previously, we are basically trying different models like Popularity based recommender system, Collaborative filtering based recommender system (user-item or item-item) etc. We will be using the Popularity based recommender system to deal with the cold start problem, where we do not have history of past purchases of a particular user or where the user is totally new.

**Variable Description**

Data set Column information for Books data set

ISBN (It is the unique number for different books)

Book-Title (It is the title of the books)

Book-Author (The author of the book)

Year-Of-Publication (It is the year when book was published)

Publisher (It is the name of the publisher)

Image-URL-S (It is URL of the books categorizing it as small)

Image-URL-M (It is URL of the books categorizing it as medium)

Image-URL-L (It is URL of the books categorizing it as large)

Columns present in the user dataset:

User-ID: Unique ID of the user

Location: Location of the user

Age: Age of the user

Columns present in the ratings dataset:
User-ID: Unique ID of the user

ISBN: Unique ID to identify a book

Book-Rating: Ratings of the book (In the range of 0-10)

**Conclusion:**

From EDA part

Maximum numbers of books are published in year 2002.

Agatha Christie has written maximum no. of books and is more than 600.

Maximum no. of books are published by Harlequin publisher.

Maximum no. of users are from USA.

Most frequent rating recieved by a book is 8.

The Book "Harry Potter and the Prisoner of Azkaban(Book 3)" has maximum Average rating and Number of rating are more 400.

Author Bill Watterson has maximum average rating.

Five Star (ME) publisher has maximum average rating(approx 8).

From Modelling part

SVD model works better than NMF model for book reccomendation as it has lower RMSE and MAE score.
