/*

    Author:: Raj Mehrotra
    Date:: 16-12-2018
    
 */


# Movie-Reviews-NLTK-Sentiment-Analysis

The Movie Reviews dataset. 

The dataset is imported from the NLTK  libray. It has 1000 positive and 1000 negative reviews. 

I have first imported the dataset into a pandas data frame which makes it easier to do the processing. The next step is to analyze the (+) and ( - ) reviews. 

I have also preprocessed the dataset by removing stop-words and  using Lemmatizing and other standard NLP techniques.

To extract the features from the text I have used the Tfidf vectorizer from the scikit. 

Lastly I have used various modellig algos from scikit to train on this data.
