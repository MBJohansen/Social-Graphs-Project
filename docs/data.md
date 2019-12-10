
## Data

The data used in the project can be divided into two parts, the plot summaries and the movie titles with actors and actress names.

The data for the plot summaries stems from two different sources. The older movies were gathered from a dataset collected by David Bamman, Brendan O'Connor, and Noah Smith at the Language Technologies Institute and Machine Learning Department at Carnegie Mellon University. The summaries and metadata had been pulled from Wikipedia and Freebase but unfortunately, since the research had been conducted in 2013, the movies in the dataset only went up to that date. To allow the analysis wanted for this project it was therefore necessary to create an additional dataset of movies released 2014 or later. These were considered the 'new' movies. The plot summaries of the new data were collected from tMDb (the Movie Database) as it presents an easy-to-use search-based API as opposed to IMDb. The selection and summaries were also short but sufficient which made them well suited for this project. In order to gather all the new titles, metadata from IMDb was used containing movie titles, genres, and release years. This collection could be utilized to drastically reduce the necessary API calls by searching only for movies also found on IMDb, released after 2013, and within genres of our interest. The grand collection of plots ultimately ended up containing around 42,000 older movies and around 70,000 newer movies. The total size of the plot summary data is 94 MB, where 72 MB of this are the summaries for old movies and 22 MB are for new movies. 



The data with movie titles and actor and actress names have been collected from IMDb by downloading some large datasets and then cleaning them to remove unwanted data. The datasets are described [here](https://www.imdb.com/interfaces/) and can be downloaded from [here](https://datasets.imdbws.com/). Only some of the datasets from that page have been downloaded. These are: "title_basics.tsv", "name_basics.tsv", and "title_principals.tsv". After downloading and extracting these files their total size is more than 2.5 GB, but after cleaning them this is cut down to two files with a total of 44 MB. This is because they contain data for short films, tv-series, movies, and so on, where only non-adult movies are considered.
Furthermore the datasets contain many columns where only a few ones are needed.

### Download
All cleaned data used in the project can be downloaded by clicking [here](/data/Data.zip).

[Next page: Analysis](analysis.md)
