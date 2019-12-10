
## Network
A network was built to examine whether certain actors dominate certain genres, in the sense that the same actors star in many different movies within the same genre.

The network consists of movies as nodes and actors as edges. If an actor stars in two different movies, those movies are connected with an edge. Nodes and edges also contain different attributes. A movie node contains the name of the movie and the genres of the movie whereas the edges only contain the actor names which connects two nodes.

The network consists of 527,345 different movies (nodes) and 19,461,220 edges, where each edge can represent one or more actors, i.e. each edge contains all the actors connecting the two given movies. Because of the size of the network it can not be shown, as it would be incomprehensible.

The initial analysis of the network included making a degree distribution.

![](images/DegreeDistribution.jpg)

It is seen that the degree distribution follows a power-law distribution. Many movies have a very low degree which makes sense since there are likely many small independent movies. Furthermore there are many movies with an extremely high degree which suggests that there are many movies using the same actors. This could include sequels to movies and is especially relevant in the Asian movies. 

When exploring the dominance of certain actors within a given genre, the notebook shows that some actors do indeed appear in many different movies within the same genre and these films may thereby seem more similar. Actors which seemed to dominate certain genres were mostly seen in Asian films. The reason for this may be that Asia simply produces a lot of films and tend to star the same popular actors again and again. This part of the analysis was also affected by the fact that the dataset is heavily dominated by Asian actors and films. This meant that none of the popular actors seen in Hollywood movies would appear in near as many films as the Asian actors.

Another interesting fact is that an old popular actor like Clint Eastwood appears in 52 different films whereas the much younger actor Dwayne Johnson appears in 46 films. Even though Dwayne Johnson is much younger (and in an earlier stage of his career) than Clint Eastwood, he appears in almost as many movies, which does indicate that newer films tend to use more of the same actors. Another reason this may be the case is that movies today are produced much faster than they were when Clint Eastwood was a big star. This is especially relevant for the type of movie Dwayne Johnson is typically seen in, ranging from silly comedy movies to shallow action movies.   


### Community detection
Community detection is another way of examining the network. Community detection is a way to find underlying communities within a network, if it exists. A community within the graph, are locally dense connected subgraphs of the network. [4] In this case the underlying community structure is the genres which, if certain actors dominate specific genres, should be somewhat easy to find. If certain actors dominate a genre, the subgraph for that genre should be more dense and should therefore be easier for the community detection algorithm to find. The algorithm partitions the graph so that the *modularity* is maximized. This means that the network is partitioned into subgraphs with dense connections within the partition but sparse connections to nodes from other partitions. [[2]](http://networksciencebook.com/chapter/9#modularity)

The network was partitioned into 173,688 different partitions and had a very high modularity value. It was clear that the majority of nodes from each genre was put into a partition, but the partitioning was quite inaccurate with regards to movie genres. The main reason for this may be that most movies has multiple genres. Another reason could be that some actors appears in many movies not only within a single genre but also across different genres. The fact that the modularity value was high means that the network does have some dense communities, thus some movies does share many of the same actors, and may therefore seem more similar. This is described in more detail in the explainer notebook.     


[Next page: Conclusion](conclusion.md)
