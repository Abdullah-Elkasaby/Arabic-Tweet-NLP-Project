# **Arabic Tweet NLP Project**

* The goal of this project is to analyze Arabic tweets and classify  them into different categories using NLP techniques. In  order to do this, we will be using a Random Forest Classifier model and comparing the performance of three different feature extraction techniques: TF-IDF, Count Vectorizer, and Binary Encoding.

## Dataset
* The dataset used for this project is a collection of Arabic tweets, collected from various sources including Twitter, news websites, and blogs. The dataset contains 10,000 tweets and is labeled with one of five categories: Positive, Negative, Neutral, News, and Other. The dataset is preprocessed and cleaned before being used for training and testing the models.

## Preprocessing
* Before the data can be used for training and testing the models,  it needs to be preprocessed and cleaned. The following steps are taken in the preprocessing phase:

## Tokenization: 
* The tweets are tokenized using the Arabic language tokenizer provided by the Natural Language Toolkit (nltk).

## Normalization:
* The tweets are normalized by removing diacritics and converting all text to lowercase.

## Stopwords Removal:
* Stopwords are removed from the tweets. A list of Arabic stopwords is used from the NLTK library.
Stemming: The tweets are stemmed using the Arabic Snowball Stemmer.

## Feature Extraction
* After the preprocessing phase, the tweets are converted into a numerical representation that can be used as input for the Random Forest Classifier model. Three different feature extraction techniques are used:

  * TF-IDF
  * Count Vectorizer 
  * Binary Encoding

## Model Training and Evaluation
* The Random Forest Classifier model is trained using the preprocessed and feature-extracted data. The dataset is split into training and testing sets, with 80% of the data used for training and 20% used for testing. The model is evaluated using the F1 score, which is a weighted average of precision and recall.


## Conclusion
* In this project, we have analyzed Arabic tweets using NLP techniques and a Random Forest Classifier model. We have compared the performance of three different feature extraction techniques: TF-IDF, Count Vectorizer, and Binary Encoding. The best performing technique is used to predict the category of new, unseen tweets. This project can be extended to include more categories or to use different models and feature extraction techniques.