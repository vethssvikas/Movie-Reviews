# Movie-Reviews
In this project, we identify the sentiments of the movie reviews from a large dataset using various models and calculate their accuracy scores
The following steps were undertaken in this project:
1. Splitting the given dataset in a 60 : 20 : 20 basis
2. Generating stop words using the nltk stop word corpus and adding more stop words relating to movies
3. Preprocessing the reviews. In this method, the following steps were taken:
a. Lower casting
b. Removal of unnecessary punctuations
c. Removal of stop words
d. Stemming
4. Training the dataset in 4 different model pipelines namely:
a. Logistic Regression
b. Linear SVC model
c. Multinomial Naive Bayes
d. Decision Trees
5. Calucation accuracy and precision score for each model was done and it was concluded that the Decision Tree model worked the best
6. Hyperparameter tuning was done using GridSearchCV and the max_depth value was calculated
7. Confusion matrix was printed
