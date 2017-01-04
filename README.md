# Blocking Restaurant Entities.
An iPython notebook used to perform blocking on restaurant entities from Yelp and Zomato.
The main purpose of this process is to bring down the number of tuples to be matched in the two tables obtained after crawling Zomato and Yelp.
tableA, which was obtained by crawling Zomato, had 3014 tuples. tableB, which was obtained by crawling Yelp, had 5883 tuples. The cartesian product of these two tables had 17731362 tuples which is too large a data set to apply an entity matching algorithm.

Hence [blocking](https://en.wikipedia.org/wiki/Blocking_(statistics)) is performed.

This project utilizes the [Magellan](https://sites.google.com/site/anhaidgroup/projects/magellan) library built in University of Wisconsin-Madison 