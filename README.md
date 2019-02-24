# Machine Learning Engineer Nanodegree

Projects developed as part of Udacity's Machine Learning Engineer Nanodegree.

## Projects

### 0. Titanic Survival Exploration
* [View Jupyter Notebook](https://github.com/ocpodariu/udacity-mlnd/blob/master/projects/titanic_survival_exploration/titanic_survival_exploration.ipynb) or [Go to project directory](https://github.com/ocpodariu/udacity-mlnd/tree/master/projects/titanic_survival_exploration)
* Explored the dataset to identify which features best predict a passenger's survival
* Used those features to create decision functions to predict the survival of the passengers

### 1. Predicting Boston Housing Prices
* [View Jupyter Notebook](https://github.com/ocpodariu/udacity-mlnd/blob/master/projects/boston_housing/boston_housing.ipynb) or [Go to project directory](https://github.com/ocpodariu/udacity-mlnd/tree/master/projects/boston_housing)
* Measured the linear correlation between features and selling price using Pearson's r
* Observed the effect of different training and testing splits on model performance
* Used learning and complexity curves to detect underfitting and overfitting
* Combined Grid Search with cross-validation to find the optimal maximum depth for a decision tree regressor
* Final model obtained an R^2 score of 0.77
* Discussed the model's applicability in a real-world scenario

### 2. SMS Spam Classification
* [View Jupyter Notebook](https://github.com/ocpodariu/udacity-mlnd/blob/master/projects/spam_classifier/sms_spam_classifier.ipynb) or [Go to project directory](https://github.com/ocpodariu/udacity-mlnd/tree/master/projects/spam_classifier)
* Transformed the SMS messages using the Bag-of-Words model
* Generated features based on the frequency of each word
* Classified SMS messages as spam or not spam with a Naive Bayes model

### 3. Finding Donors for CharityML
* [View Jupyter Notebook](https://github.com/ocpodariu/udacity-mlnd/blob/master/projects/finding_donors/finding_donors.ipynb) or [Go to project directory](https://github.com/ocpodariu/udacity-mlnd/tree/master/projects/finding_donors)
* Evaluated the performance of different supervised algorithms in identifying individuals making more than $50,000
* Preprocessed the data by scaling numerical features, one-hot encoding categorical features and applying logarithmic transformations on features with skewed distribution
* Built a pipeline to quickly evaluate the performance of different algorithms
* Analyzed AdaBoost's performance in relation to the maximum number of estimators
* Identified the top 5 most important features and analyzed the effects of feature selection on AdaBoost's performance
