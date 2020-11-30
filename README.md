# Spam-SMS-Detection

Created a pipeline of Natural language processing for finding a SMS will be a Ham or Spam.

1. First the message is processed using Processing text function ie, removed any (comma, question mark etc.)
2. Used Tfidf Transformer (TF-IDF stands for term frequency-inverse document frequency)
3. Using MultinomialNB from Naive Bayes Classifier.
4. Creating the Pipeline
pipeline = Pipeline([('Text',CountVectorizer(analyzer = processing_text)),
 ('tfidf',TfidfTransformer()),
 ('classifying', MultinomialNB())])
