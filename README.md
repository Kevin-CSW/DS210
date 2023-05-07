# DS210 Final Project (Bitcoin Tweets Analysis)
The program analyzes a dataset of tweets containing hashtags related to Bitcoin. 
It processes the data to build a graph where the nodes are hashtags and the edges 
represent the co-occurrence count of pairs of hashtags in the dataset. Using 
Dijkstra's algorithm, the program then calculates the shortest path distances 
between the hashtag "Bitcoin" and all other hashtags in the graph. Finally, 
the program prints the top N hashtags with the smallest distances from the 
hashtag "Bitcoin", where N is a user-defined threshold. This helps in understanding 
which hashtags are more closely related to the "Bitcoin" hashtag based on their 
co-occurrence in the dataset. 
