# SentiHotel
SentiHotel is a sentiment analysis of hotel review dataset.
Dataset Preprocessing steps:
1) Dealing with null Values
2) Removing Html entities
3) Removing punctuations
4) Lowercase conversion
5) Tokenization
6) Removing Stopwords
7) Word Lemmatization
   Data Visualization: Word Cloud
Vectorization:
1) CountVectorizer
2) TF-IDF

Classifiers
1) Decision Tree
2) Random Forest
3) SVN
4) KNN

After applying classifiers and hyperparameter tunning following are the results for the following performance metrices:
TF-IDF
Classifiers	  Accuracy Precision Recall	F1 Score
Decision Tree	  85.75%	85.23%	85.75%	85.41%
Random Forest	  85.82%	85.29%	85.82%	85.46%
SVM	            85.82%	85.29%	85.82%	85.46%
KNN	            80.33%	81.50%	80.33%	78.62%

Count Vectorizer
Classifiers	  Accuracy Precision Recall	F1 Score
Decision Tree	  86.50%	85.91%	86.50%	86.12%
Random Forest	  86.86%	86.26%	86.86%	86.46%
SVM	            86.86%	86.26%	86.86%	86.46%
KNN	            82.38%	82.21%	82.38%	81.98%

We can notice that with count Vectorizer the classifiers had better prediction rate.

Tech Stack: NLTK, SKLEARN, Pandas, Wordcloud



