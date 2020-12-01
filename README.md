# Spam-SMS-Detection

Created a pipeline of Natural language processing for finding a SMS will be a Ham or Spam.

1. First the message is processed using Processing text function ie, removed any (comma, question mark etc.)
2. Used Tfidf Transformer (TF-IDF stands for term frequency-inverse document frequency)
3. Using MultinomialNB from Naive Bayes Classifier.
4. Creating the Pipeline<br/>
pipeline = Pipeline([('Text',CountVectorizer(analyzer = processing_text)),
 ('tfidf',TfidfTransformer()),
 ('classifying', MultinomialNB())])
 <br/>
 <br/>
 <br/>
 **If you enjoy this project, please consider <a href="https://www.buymeacoffee.com/idevesh" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: 41px !important;width: 174px !important;box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;" ></a>
 to continue developing and maintaining it.**

### Show some ❤️ by starring my repository! ![](https://visitor-badge.glitch.me/badge?page_id=idevesh.Spam-SMS-detection&style=flat-square&color=0088cc)
