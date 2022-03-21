# Sentiment Analysis on Movie Reviews
Sentiment analysis of a movie review can rate how positive or negative a movie review is and hence the overall rating for a movie.

## Working Principle
First we will clean the data. Then we will represent our data as a collection of words or tokens. After that breaking the documents down into term frequencies, then transforming them into TD-IDF value. With X and y as our feature matrices of TD-IDF values and target vector of sentiment values respectively, we are ready to split our dataset into training and test sets. Then, we will fit our training set into a Logistic Regression model. Finally, we will be passing our test data to predict the output

## APPROACH
-Cleaned and preprocessed the data.

-Perform feature extraction using methods such as Count Vectorization, term frequencies, and inverse document frequencies, natural language toolkit.

-Built and employed a Logistics Regression model using scikit-learn.

-Model evaluation using Javan’s Accuracy Score and Confusion Matrix.

## Packages Used
1. nltk
2. sklearn
3. re
4. CountVectorizer
5. TfidfTransformer
6. LogisticRegressionCV
7. numpy 
8. pandas

## OS used
Windows 10
