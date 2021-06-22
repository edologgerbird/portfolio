# Data Science Portfolio
 
## Project 1: Fake News Classifier (USA Presidential Elections 2016)

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


![Predictor Interface](https://github.com/edologgerbird/portfolio/blob/main/assets/fake-news-form1.png "Predictor Interface")


![Predictor Interface](https://github.com/edologgerbird/portfolio/blob/main/assets/fake-news-form2.png "Predictor Interface")


## Project 2: Malaria Classifier from Cell Image

- Developed an classifier to identify if a given cell is uninfected or parasitised by malaria based on an image of the cell.
- Utilised the Malaria dataset from the Tensorflow Datasets package.
- Constructed tensors representing the cell images
- Trained a Deep Learning model using containing dense and convolutional neural network layers
- Accuracy on test set: 0.9427
- AUC Score on test set: 0.9843


![Example](https://github.com/edologgerbird/portfolio/blob/main/assets/malaria-examples.png "Example")
