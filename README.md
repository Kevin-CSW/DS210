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

All necessary files for this project are included in the DS_210_final_project folder. The folder contains a CSV file named "Bitcoin_tweets_dataset_2," which serves as the primary dataset for this project. This dataset was obtained from Kaggle: https://www.kaggle.com/datasets/kaushiksuresh147/bitcoin-tweets?select=Bitcoin_tweets_dataset_2.csv.

In addition to the dataset, the zip file contains seven source files located in the 'src' directory and a single test file in the 'test' directory. The 'src' directory includes the following files: 'lib', 'main', 'hashtag_loader', 'hashtag_processor', 'weighted_graph_creator', 'shortest_path', and 'rank_distance'. A detailed explanation of each file's functionality will be provided in the accompanying write-up.
