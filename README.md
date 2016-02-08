# Sentiment-Analysis-nltk

Steps involved are:
1. Collection of training and testing tweets
2. Preprocessing of the training tweets by splitting the words , removing the words with length < 3 and also removing the stopwords. 
   There is more to pre-processing by bringing all the words to one consistent level etc
3. Creating feature using the words which have high frequency
4. Checking the word features in each of the training tweets (Extract featuring)
5. Traditional NaiveBayesClassifier from nltk module to train on the training set
6. Testing the model on the testing tweets.
