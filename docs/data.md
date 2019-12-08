
## Data

The data used in the project can be divided into two parts, the plot summaries and the movie titles with actors and actress names.
**TO DO: The data for the plot summaries...**

The data with movie titles and actor and actress names have been collected from IMDb by downloading some large datasets and then cleaning them to remove unwanted data.
The datasets are described [here](https://www.imdb.com/interfaces/) and can be downloaded from [here](https://datasets.imdbws.com/).
Only some of the datasets are downloaded, these are: title_basics.tsv, name_basics.tsv, and title_principals.tsv.
After download and extracting these files their total size is more than 2.5 GB but after cleaning them it is cut down to two files and a total of 44 MB.
This is because they contain data for short films, tv-series, movies, and so on, where only non-adult movies are considered.
Furthermore the datasets contain many columns where only a few ones are needed.

### Download
All cleaned data used in the project can be downloaded by clicking [here](/data/Data.zip).

[Next page: Analysis](analysis.md)
