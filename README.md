# Spam_Ham
## Aim 
Predict message is spam or ham. <br/>

## Input
File containing labels for spam and ham messages.<br/>

## Libraries used 
sklearn , re <br/>

## Steps
1) Normalizing message's words using (stopwords,punctutions)<br>
2) Using tfidfvectorizer giving words their occurnce value according to the formulae of tdidf <br>
3) Transforming the tfidf vector to bag of words<br>
4) Using Navie Bayes predicting algorithm traning the train set<br>
5) Finally predicting for the test set<br>

## Outcome
Test has an  Acuraccy =  1348 / 1394  =  96.70014347202296
