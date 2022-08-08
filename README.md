# Arabic-Sentiment-Analysis
Arabic Sentiment Analysis using deep learning and machine learning and optimzation methods
# Arabic Sentiment Analysis
Sentiment analysis was nominated as a hot research topic a decade ago for its increasing importance in analyzing the people's opinions extracted from social media platforms. Although the Arabic language has a significant share of the content shared across social media platforms, its content's sentiment analysis is still limited due to its complex morphological structures and the varieties of dialects.

## Libraries


## Dataset

ArTwitter was collected from Twitter on different topics: politics and arts. It consists of 1951 Arabic tweets annotated in positive and negative labels. It is split into 80% training set and 20% testing set. The training set contains 794 positive and 766 negative classes. The testing set includes 199 positive and 192 negative classes. 
https://www.kaggle.com/datasets/mksaad/arabic-sentiment-twitter-corpus

##  Data Pre-Processing 
Because the text of tweets is known to be noisy, it must be cleaned and pre-processed before being analyzed. 
- Cleaning Tweets: The removal of irrelevant information is crucial to cleaning Twitter data due to its noisy nature. By removing non-Arabic letters, digits, single Arabic letters, and special symbols, removing URLs, removing Emails, and removing hashtags. 
- Tokenization only involves segmenting the sentences into parts. 
- Removing Arabic Stop Words
-  Stemming
- Cleaning Emoticon's emotions. 
- 
## Data splitting
ArTwitter was separated into two sets: the training set and the testing set, with the training set accounting for 80\% of the dataset and the testing set accounting for 20\% of the dataset. The training set is used to train and optimize models. The testing set (unseen set) is used to evaluate~models. 

## Machine Learning
 -  TF-IDF with different sizes of n-gram was used to extract the feature 
 - Five regular machine learning ML models, namely Decision Tree (DT), 
   K-nearest Neighbors (KNN), Random Forest (RF), Naive Bayes (NB)
   were used. 
 - Grid search with cross-validation is used to optimize ML
   algorithms and improve ML algorithms performance.
   
## Deep Learning
- Arabic contains a pre-trained distributed word embedding for the Arabic language that includes different word embedding models in Tweets and Wikipedia. We used Twitter-CBOW word embedding with a 300 vector size. 
- We applied three deep learning models: Recurrent Neural Network (RNN), Long Short-Term Memory (LSTM), Gated Recurrent Unit (GRU)
- We optimized DL models using KerasTuner.  
https://keras.io/keras_tuner/



