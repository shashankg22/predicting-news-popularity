# Predicting the Online News Popularity

### Business Problem:

Mashable Inc is a digital media website founded in 2005. It has over 9.5 million twitter followers and over 6.5 million fans on Facebook. Predicting the popularity of news can be formulated in many ways such as regression or classification. Coming up with the attributes that describe a popular news article or predicting whether a specific article is popular or not helps the business in reducing customer churn and also acquire new segments.

### Business Objective:
To predict whether the given news article is popular or not, based on a number of features.

### Description:
The data set summarizes a heterogeneous set of features about articles published by Mashable in a period of two years. There are 61 attributes out of which 58 are predictive attributes, 2 non- predictive and 1 goal field. Our main aim is to conduct a research on whether the given news article item is popular or not.

### Data Source:
http://archive.ics.uci.edu/ml/datasets/Online+News+Popularity

### Methodology:
The given dataset contains number of shares as the predictor variable. We converted it to a categorical variable that tells whether the news article is popular or not. We find the median of the variable ‘shares’ and take the value as the dividing factor between the popular and the unpopular category. We then made use of classification algorithms like logistic regression, random forest classifier and SVM (support vector machine) to build models. We evaluated the models with appropriate evaluation strategies and come up with the model that gives the best possible accuracy.

### Applications:
We used of R studio for the purpose of coding and Tableau for any visualizations.
