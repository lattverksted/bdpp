# bdpp
Text Sentiment Analysis with PySpark

Application of Big Data-Parallel Programming to NLP (text sentiment analysis)
Classification of movie reviews (Positive or negative)
with the PySpark library;
Preprocessing, IDF-TF, Model, MLIB Pipeline, RDD

We want to learn to classify movie reviews according to the emotional polarity : positive or negative. 
This is a textbook binary classification problem that we will tackle in a supervised learning fashion.
We have found a dataset of labeled movie reviews from IMDB. It contains 50,000 reviews split evenly into 25 000 training and as many testing samples.
We will use a SVM model to solve this classification model for a good generalization error.



The model reaches a test accuracy of 87.3% which is not bad given that we simply count words regardless the interaction between them and that no hyper-parameter tuning has been performed yet. The train accuracy is 88.4% which is not far from the test accuracy. Hence, the model is not over-fitting.   
The accuracy could be improved by cleaning further the feature vector further and also using a Random Forest model.

