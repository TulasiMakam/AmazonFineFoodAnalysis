# AmazonFineFoodAnalysis
Demonstration to perform EDA(Exploratory Data Analysis), Data cleaning, Data Visualization and Text Featurization(BoW, TF-IDF,Word2Vec,Weighted TF-IDF Word2Vec). And Built a Machine Learning model using Naive Bayes Algorithm.

# Objective:

From the text reviews of Amazon food products, determine whether the reviews are positive or negative.
Data source:https://www.kaggle.com/snap/amazon-fine-food-reviews

All data in one sqlite database. 568,454 food reviews Amazon users left up to October 2012.
Number of reviews: 568,454
Number of users: 256,059
Number of products: 74,258
Timespan: Oct 1999 - Oct 2012
Number of Attributes/Columns in data: 10

# Attribute Information:

Id
ProductId - unique identifier for the product
UserId - unqiue identifier for the user
ProfileName
HelpfulnessNumerator - number of users who found the review helpful
HelpfulnessDenominator - number of users who indicated whether they found the review helpful or not
Score - rating between 1 and 5
Time - timestamp for the review
Summary - brief summary of the review
Text - text of the review

# EDA, NLP and Text Preprocessing

1. Performed Data Cleaning & Data Preprocessing by removing unneccesary and duplicates rows and for text reviews removed html tags, punctuations, Stopwords and Stemmed the words using Porter Stemmer
2. Documenting the concept
3. Plotted TSNE plots for Different Featurization of Data viz. BOW, tfidf, Avg-Word2Vec and tf-idf-Word2Vec.

# Machine Learning Model using Navie Bayes:

Applied Naive Bayes algorithm using Bernoulli NB and Multinomial NB on Different Featurization of Data viz. BOW, tfidf.
Evaluated the test data on various performance metrics like accuracy, f1-score, precision, recall,etc. also plotted Confusion matrix using seaborne.

# Conclusion:

Performed Data, cleaning, EDA, t-SNE to understand the select the best features and then applyied Navies Bayes algorithm for machine learning model to determine whether the review is positive or negative. 
