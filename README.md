# linking-posts-stack-overflow

Initial analysis -
Projecting a pie chart by calculating the percentage of links in Questions, Answers, and Comments.
Projecting a bar chart by calculating the number of links under 3 categories for Posts, Answers, and Comments -
Internal
  -Internal to Stack exchange (ignored as the count was insignificant compared to other two)
External links
  -Projecting a bar chart of top 20 domains in external links.




Implementation-

For building the recommendation system we used the Doc2vec model which is one of the techniques used in the research paper

Preprocessing 
  -Removed the stop words, punctuation marks, and Lemmatization is performed.
  -Created a new column tokenized_title which contains the list of words for the combined text - Title and Body of each record
  
List of documents are formed for each row

TF-IDF, Word2Vec, Doc2Vec model is trained with necessary input parameters and is saved
