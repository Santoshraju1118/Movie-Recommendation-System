# Movie-Recommendation-System

- ▶️ [Demo | Movie Recommendation System ](https://nbviewer.jupyter.org/github/Santoshraju1118/Movie-Recommendation-System/blob/master/movie%20recommendation%20system.ipynb) - Movie Recommendation System.

A movie recommended system using IMDB datasets.
IMDb (Internet Movie Database) is an online database of information related to films, television programs, home videos, video games, and streaming content online – including cast, production crew and personal biographies, plot summaries, trivia, ratings, and fan and critical reviews.

As of January 2020, IMDb has approximately 6.5 million titles (including episodes) and 10.4 million personalities in its database, as well as 83 million registered users.

Imdb doesn't give rating. It shows average rating given by users for that particular movie. Users can give movie a rating between 1 to 10. And average for that movie is calculated and shown to other users. And for imdb 250, they have devised a specific formula for calculating the rating and listing the movie accordingly.

The following formula is used to calculate the Top Rated 250 titles. This formula provides a true 'Bayesian estimate', which takes into account the number of votes each title has received, minimum votes required to be on the list, and the mean vote for all titles:

weighted rating (WR) = (v ÷ (v+m)) × R + (m ÷ (v+m)) × C

Where:->

R = average for the movie (mean) = (Rating)

v = number of votes for the movie = (votes)

m = minimum votes required to be listed in the Top 250 (currently 25,000)

C = the mean vote across the whole report

# What are IMDb ratings?

IMDb registered users can cast a vote (from 1 to 10) on every released title in the database. Individual votes are then aggregated and summarized as a single IMDb rating, visible on the title’s main page. By “released title” we mean that the movie (or TV show) must have been shown publicly at least once (including festival screening).

Users can update their votes as often as they’d like, but any new vote on the same title will overwrite the previous one, so it is one vote per title per user.

# How do you calculate the IMDb rating displayed on a title page?

We take all the individual ratings cast by IMDb registered users and use them to calculate a single rating. We don't use the arithmetic mean (i.e. the sum of all votes divided by the number of votes), although we do display the mean and average votes on the votes breakdown page; instead, the rating displayed on a title's page is a weighted average. To display the breakdown of the detailed votes, click the number of votes located directly below the average IMDb user rating. For example, see the User rating breakdown for Inside Out.

The IMDb weighted average does not change upon receipt of each new vote but instead is updated numerous times per day.

A TV series rating is not the weighted average of the ratings of individual episodes. Instead, customers vote separately for the rating of the series as a whole via each title’s series page.

