# yelp_rating_prediction
 Exploring machine learning and graph embedding concepts to build model to predict user rating for various restaurants from yelp data
 
 ### Notebooks
 - MLPNN_rating_prediction -  MLPNN model trained on top 10 restaurant category yelp data for rating prediction
 - RF_rating_prediction -  Random forest model trained on top 10 restaurant category yelp data for rating prediction
 - RF_with_embeddings_rating_prediction -  Random forest model trained on top 10 restaurant category yelp data along with node embeddings obtained for restaurant categories for rating prediction
 - Build relevant yelp relational database for Neo4j -  Generates relational database files (json format) from top 10 restaurant yelp data - used to build graph databse in Neo4j - files are saved in Neo4j dataset folder -> they have to be later moved to Neo4j relevant import library foler when a database is initialized in Neo4j
 - Neo4j_cypher_queries - cypher queries used to load json files and create yelp graph database in Neo4j with node and edge properties + queries to extract graph embeddings.

### Folders
- Dataset - download yelp dataset from (https://www.yelp.com/dataset) and save users.json, business.json and reviews.json files here
- Neo4j dataset - files from "Build relevant yelp relational database for Neo4j" are saved here
- results - screenshots from Machine Learning model results and Neo4j

