# Engage-project-3

This project is based on building a movie Recommendation engine.

There are different types of Recommendation Engines. Here, we made content based one.

We check the similarity between movies using cosine method.

Basically the texts in each movies and their descriptions will be mapped into the vectors based on number of similarities. After creating vectors for each movie the distance between each vector define the similarities. If the distance is less then it has more similarity. Here for vectors we talk about angular distance which is cosine theta (since cos(0º) = 1, cos(90º) = 0 where Theta is angle between the vectors).

Using the above method we check the similarity with each and every movie with the given id and give the 10 top most recommended movies according to their previous interests. 
