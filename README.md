# Sentiment Analysis of Amazon Reviews  
Used bag-of-words representations of Amazon reviews to predict the sentiments that the reviews express. The bag-of-words representation is constructed from counts of the top 1,000 words appearing in the reviews, excluding a list of such stop words as "and" and "the." These words are also stemmed, so that words such as "want" and "wanted" are collapsed into a single feature. For each review, a label of 0 indicates a 1 or 2-star review, while a label of 1 indicates a 4 or 5-star review.  <br>

Train the model with "training_data.txt", and test the predictions with "test_data.txt". <br>

Methods tried: Lasso/Ridge Regression, SVM, Logistic Regression, XGBoost, MLPClassifer, Tensorflow backened Neural Networks, Random Forests, Voting/Stacking methods. <br>

Final Test Accuray: 86%

