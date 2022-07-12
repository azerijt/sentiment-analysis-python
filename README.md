# sentiment-analysis-python

For this task, I build a model to predict the sentiment of movie reviews from the Stanford Sentiment Treebank binart classification dataset. This dataset consists of reviews labelled 1 for positive and 0 for negative.

This task requires that I build a model to predict the sentiment (either positive or negative) of movie reviews. To do so, I first must transform the text input into numerical data for processing. The simplest means of doing this is to create a dictionary of words with term frequencies. First, the phrases must be tokenized into words, and then encoded as integers or floats to input into an algorithm.

I compare vectorizers, models and hyperparameter tuning to create a model that achieves 83.6% accuracy on test data.
