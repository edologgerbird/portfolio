# Data Science Portfolio
 
## Fake News Classifier (USA Presidential Elections 2016)

- Developed models to classify if a given news article related to the USA Presidential Election 2016 is fake or reliable news. Positive class indicates fake news and negative class indicates reliable news.
- Constructed the model based on the Kaggle Fake News Dataset which contains 20800 labeled news articles, of which about half are fake news articles and the other half are reliable news articles.
- Inspected for inherent patterns using unsupervised learning (K-means clustering) that will discriminate the news articles between fake and reliable, without referencing to the given labels.
- Conducted both Hashing Vectorisation and IF-IDF Vectorisation of the text data to determine which form of NLP Vectorisation produced to best performing model.
- Tested Passive Aggressive Classifier, Logistic Regression and XGBoost Regression Classifier. 
- XGBoost Regression Classifier on TF-IDF Vectorisaton was the best performing model, with an accuracy of 0.9978 on Test Data.
 - Built a client facing UI using Flask API, WTForms and Jinja2. 

#### XGBoost Classifier with TF-IFD Vectorisation (best performance)

Accuracy: 0.9978365

        precision    recall  f1-score   support

    0       1.00      1.00      1.00      2046
    1       1.00      1.00      1.00      2114


![Predictor Interface](https://github.com/edologgerbird/fake-news-classifier/blob/main/assets/form1.png "Predictor Interface")


![Predictor Interface](https://github.com/edologgerbird/fake-news-classifier/blob/main/assets/form2.png "Predictor Interface")
