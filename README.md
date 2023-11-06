# Sentiment-Analysis-IMBD

Sentiment analysis identifies emotionally-charged texts. This tool can be extremely useful in business when evaluating consumer reactions to a new product. A human would need several hours to analyze thousands of reviews. A computer will do the same in a couple of minutes.
Sentiment analysis works by labeling text as positive or negative. Positive text is given a "1", and negative text is assigned a "0".

## Task
Train a logistic regression model to determine the tonality of the reviews. Use TF-IDF vectors for lemmatized reviews as features.
The train part of the dataset is in the imdb_reviews_small_lemm_train.tsv file, the lemmatized reviews are in the review_lemm column (so you don't have to lemmatize reviews yourself), and the target is in the pos column (0 - negative review, 1 - positive review).

Use the trained classification model to determine the prediction results for the test sample of reviews from the imdb_reviews_small_lemm_test.tsv file. Save the predictions to the pos column. The model accuracy should be at least 0.82.

Save the table with results as a CSV file. 
