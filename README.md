# Movie-recommendation-system

Content Based Recommender System recommends movies similar to the movie user likes and analyses the sentiments on the reviews given by the user for that movie.

The hollywood movie details upto the year 2017 are obtained from kaggle. The remaining details for the years 2018, 2019 and 2020 are obtained by webscaping from wikipedia and TMDB api. The webscraping was performed using Beautiful soup package in python. Another innovative package AutoScrapper was also implemented in python to scrape 2020 movie details which eases the scraping process and was found to be easy to use than beautiful soup. The specific details from the scraped data like title, genre, runtime, rating, poster, etc are then obtained by performing extensive text cleaning procedures.

Create an account in https://www.themoviedb.org/, click on the API link from the left hand sidebar in your account settings and fill all the details to apply for API key. If you are asked for the website URL, just give "NA" if you don't have one. You will see the API key in your API sidebar once your request is approved.

# Sources of the datasets

[IMDB 5000 Movie Dataset](https://www.kaggle.com/datasets/carolzhangdc/imdb-5000-movie-dataset)

[The Movies Dataset](https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset)

[List of movies in 2018](https://en.wikipedia.org/wiki/List_of_American_films_of_2018)

[List of movies in 2019](https://en.wikipedia.org/wiki/List_of_American_films_of_2019)

[List of movies in 2020](https://en.wikipedia.org/wiki/List_of_American_films_of_2020)

