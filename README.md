# User Business Recommendation-Engine

<h3>Purpose of the project: </h3>
This project is designed to recommend user similar businesses based on their reviews given. 
It focuses on the implementation of a topic modelling algorithm on textual data and stores textual data in a graph database to gain valuable insights for a recommendation system. 

<h3>Approach:</h3> 
1. To design a database schema to store theunstructured data in the form of nodes and relation using cypher. 
2. To import the data into a jupyter environment for further exploring and analysing the data using exploratory data analysis, machine learning and natural language processing libraries to perform topic modelling on the textual data imported from the Neo4j. 
3. The topics generated in conjunction with textual data were then be imported back again to Neo4j to explore further insights about data.

<h3>Technology used: </h3>
Database: Neo4j
Programming: py2neo, nltk, sklearn, datetime, pandas, matplotlib, wordcloud, scipy, LDA
Data Vizualization: pyLDAvis, cypher

<h3>Results:</h3>

![output2](https://user-images.githubusercontent.com/33175569/145482170-443f4e49-f2e1-4893-9434-03632c6e6047.png)

![output1](https://user-images.githubusercontent.com/33175569/145482158-26f2b474-f227-475a-b9bb-01f166a37f73.png)

![output3](https://user-images.githubusercontent.com/33175569/145482205-2dff19a8-cc9c-4dda-aafa-8eaa7a973a0f.png)

![Recommendation2_Yelp](https://user-images.githubusercontent.com/33175569/145482213-40bb4d7c-1691-4f2a-89d4-382cb33161d8.PNG)

![Topics_Yelp](https://user-images.githubusercontent.com/33175569/145482232-f53188f5-e467-41bd-a90f-5d1d6e2c07d1.PNG)

![YElp_jsondata](https://user-images.githubusercontent.com/33175569/145482240-1660aebb-53ae-400a-aa3b-70a877989741.PNG)

![Yelp_Neo4j_output](https://user-images.githubusercontent.com/33175569/145482249-f5ee0427-2e22-4cae-9dac-26e08e2670e0.PNG)



