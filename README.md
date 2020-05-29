# Spam-Classifier
[![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/made-with-python.svg)](https://forthebadge.com)[![forthebadge](https://forthebadge.com/images/badges/its-not-a-lie-if-you-believe-it.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/built-by-developers.svg)](https://forthebadge.com)

<p align="center">
  <a href="https://github.com/ksdkamesh99/Spam-Classifier">
    <img src="images/front.jfif" alt="Logo">
  </a>
</p>

## 📌 Introduction:-

A Natural Language Processing with SMS Data to predict whether the SMS is Spam/Ham with various ML Algorithms like multinomial-naive-bayes,logistic regression,svm,decision trees to compare accuracy and using various data cleaning and processing techniques like PorterStemmer,CountVectorizer,TFIDF Vetorizer,WordnetLemmatizer.
It is implemented using LSTM and Word Embeddings to gain accuracy of 97.84%.

## ✔❌Accuracy ❌✔:-
| Text Preprocessing Type              | Logistic Regression | Multinomial NB | Support Vector Machine  | Decision Tree |
|--------------------------------------|---------------------|----------------|-------------------------|---------------|
| TFIDF Vectorizer + PorterStemmer     | 96.68%              | 97.30%         | 98.47%                  | 96.68%        |
| CountVectorizer + PorterStemmer      | 98.65%              | 98.56%         | 98.74%                  | 97.84%        |
| CountVectorizer + WordnetLemmatizer  | 98.56%              | 98.29%         | 98.38%                  | 97.75%        |
| TFIDF Vectorizer + WordnetLemmatizer | 96.41%              | 97.48%         | 98.47%                  | 96.86%        |


## WorkFlow:-
![Workflow of SMS spam Classifer](workflow.gif)

## 🏁 Datasets Used:-
* The dataset used is SMS Spam Dataset created by UCI Machine Learning.This dataset is downloaded in kaggle.You can download it [here](https://www.kaggle.com/uciml/sms-spam-collection-dataset/download).
* Reference for this dataset can be found [here](http://www.dt.fee.unicamp.br/~tiago/smsspamcollection/)
## 📧Contact:-
For any kind of suggesstions/ help in models code Please mail me at ksdkamesh99@gmail.com.

## 📜 LICENSE
[MIT](https://github.com/ksdkamesh99/Spam-Classifier/blob/master/LICENSE)
