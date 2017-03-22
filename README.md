# IMDB_sentimental_analysis
This is a part of a excercise on Kaggle using word2vec for sentimental analysis on IMDB Database

Here I have written four different types of scripts for the analysis

1.TFIDF_SVM : I used TFIDF vectorizer in python with a limit on number of features and Applied Linear SVM is sklearn.

2.word vector model : Word2Vec from gensim is used for word embedding words to vectors.In this excercise,we took both the train data and test data to create a vocabulary and then compute a dictionary with key as word and value as vector. The average of word vectors for all the words in the review is taken as feature vector for our classification.

3.min max word2Vec for Sentimental Analysis : Same as 2 but here we have used concatenation of minimum and maximum vectors obtained by taking coordinate wise minimum and maximum values.

4.Word_Vectors with phrases : In this tutorial, we have computed the possible phrases using "Phrases" class in gensim.models . The sentences with phrases in the review are then sent for computing the model.Here too i am using average of word vectors per review as feature
