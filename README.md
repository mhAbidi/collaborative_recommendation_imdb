# collaborative_recommendation_imdb


This is a training project to demonstrate the use of collaborative filter in a real world application.


Here we will be working on IMDB movie ratings dataset.

The goal over here is to create an algorithm which can easily and precisely predict which movie the user will enjoy and which movies the user will hate.

Given how the collaborative filtering works, this algorithm is really well suited for such an application.
In collaborative filtering systems; the user plays an active role.
For this system to work properly, first it needs a lot of active actors or sensors (or as in our case 'users').
Then we make smaller and finer groups of the actors based on their taste or "feature similarity".

What does it all mean?
  If user1 and user2 give 5 star to movie A and B both, and 1 star to movie C; and only user1 has given 5 star to movie D
  with the help of collaborative filtering we can easily deduce that user2 will also enjoy movie D, as the people of that taste group have already showed great interest in that.

In real world application its not 2 users, and not 4 movies.
There are thousands and thousands of movies, and even bigger audience.
In such a huge ocean of content, the system should provide the user the best movie according to the users' taste.

And thats what collaborative filtering is all about.


1. Where to start? Get the data.
  First we gather the data from a reputable source.
  After we have the dataset; we need to make some changes to it; if needed a few changes to the data structure; cleaning the data and such.
  Then we have to take out a test set; we will use this later to check how good the model is.
 
 
