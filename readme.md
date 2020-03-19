# Overview

A Naive Bayes classifer for movie reviews sentiment analysis.  

# Dataset 

[Movie Review Dataset](https://www.cs.cornell.edu/people/pabo/movie-review-data/) is a movie review sentiment analysis dataset. It was made available in 2004 by Bo Pang and Lillian Lee. Around 2,000 moview reviews are included in the dataset that are annonated as either `positive` or `negative`. It is about 3.8MB in size and can be
downloaded from this [link](https://raw.githubusercontent.com/nltk/nltk_data/gh-pages/packages/corpora/movie_reviews.zip).


```
Sentiment Polarity Dataset Version 2.0
Bo Pang and Lillian Lee

http://www.cs.cornell.edu/people/pabo/movie-review-data/
```

Note: the dataset was not uploaded in this repository.
# Model

A Naive Bayes classifier with the 2000 most common words in the corpus as the feature vector.

It was trained from scratch on the training data using [scikit-learn](https://scikit-learn.org/).

# Metrics

The model achieved 77% accuracy on the validation set (random 20% subset of the training dataset).