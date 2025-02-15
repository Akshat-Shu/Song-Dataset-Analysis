## Movies Dataset Analysis

An analysis of the Songs Dataset using basic data analysis methods, Curated as a part of the selection process for Kharagpur Data Analytics Group

* Generated embeddings for three keywords for every song in the dataset and compared the Bag-of-Words and TF-IDF Embedding models.
* Performed Principal Component Analysis on the Embeddings generated for each keyword and reduced the dimensionality to 2 for all of them
* Came up with a reduced embedding definition in order to visualize individual songs as points in the 3D space.
* Performed K-means clustering on the reduced embeddings in order to cluster songs and found out the Silhouette score for this clustering using Ground Truth (Genre) values.
* Using the clustering, assigned genres to new datapoints via a binomial distribution using only their keywords

### Further Analysis
* Gained insights into the dataset looking at how Genres and Keywords relatte to each other
* Analyzed the Keyword-Keyword co-occurence to gain further insights

See [Report](Movies_Dataset_Report.pdf) 