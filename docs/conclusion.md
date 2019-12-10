
## Conclusion

The project set out to determine the variety of movies within genres, comparing newer and older movies. The three chosen factors for analysis were; word frequency analysis, sentiment analysis, and actor collaboration analysis. While sentiment analysis did not provide strong evidence for a change in tone for modern movies compared to older movies, all three approaches did present some interesting outtakes.

The first approach revolved around word clouds within genres and presented some interesting differences between newer and older movies. There were some distinct differences between the two groups in some of the genres while others remained quite similar. The similar genres such as action, horror, and a few more, are quite understandable due to the genres typically being quite similar in essence. In contrast, when looking at genres such as animation and crime there are distinct differences in the word clouds. The animation genre is interesting as the old movies are quite clearly dominated by certain classics while the newer animation movies have seen a much vaster variety in direction. The crime genre is also interesting as the old movies seem to be dominated by a collection of Indian movies, introducing a selection of very different words as opposed to the new movies. Overall, the word clouds may not have suggested a significant and constant difference between new and old movies, but does present some interesting insights into the plots of movies within certain genres. It becomes quite clear that certain movie genres may tend to be more similar due to the clear dominance of a specific set of words. Across most genres, the words: "find" and "one" are clearly the most frequent. This may suggest a certain trend in the direction of the average movie. The word clouds do present some interesting insight into movies overall, but does not provide clear evidence that newer movies have become more similar in comparison to old movies.

The second approach utilized sentiment analysis to try and see the change in tone for the two categories of movies. This approach did not provide any clear evidence that new and old movies have really changed within genres. However, it is quite interesting to compare the sentiment of summaries between different genres. The values calculated does suggest slim differences between different genres but does not suggest that the plots of certain genres are more or less positive. This in itself is quite interesting, but does adhere to the general recipe of a movie. There will typically be some climax, conflict and resolution whether the movie is an animation film or action film. Therefore it is quite understandable to see the very similar sentiment scores.

**TODO: THE NETWORK**






### Future work

For future work, it would be interesting to pull back the category of "old" movies to a much earlier release year to see if the results would then be different. Differences between the plots of movies may be more clear if the year gap is larger. This could for example be done by separating movie plots into decades, i.e. such that all movies from the 1990's are in one category, all 1980's movies are in another, and so on. This could show the change over time in more details but also make it possible to compare for example movies from the 1980's to movies from 2010's to potentially see a larger difference.

Another option for further development would be to use tMDb for both the summaries of old movies and new movies, thereby reducing the potential bias of different sources. However it should be noted that the summaries of tMDB and Wikipedia are open community created databases which mean the plots can be written by many different people. It would also be interesting to limit the dataset to only English films to remove the domination of Asian influence in the network analysis and some genres. This could be done quite easily using the tMDb API's discover query. This query allows very efficient filtering of data including the specification of original movie language.

[Back to Introduction](index.md)
