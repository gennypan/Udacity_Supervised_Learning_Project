# Udacity_Supervised_Learning_Project
## Getting Started
In this project, I will evaluate several supervised algorithms to accurately model individuals' income using data collected from the 1994 U.S. Census. Then I will choose the best candidate algorithm from preliminary results and further optimize this algorithm to best model the data. My goal with this implementation is to construct a model that accurately predicts whether an individual makes more than $50,000.  

The dataset for this project originates from the [UCI Machine Learning Repository (https://archive.ics.uci.edu/ml/datasets/Census+Income). The datset was donated by Ron Kohavi and Barry Becker, after being published in the article _"Scaling Up the Accuracy of Naive-Bayes Classifiers: A Decision-Tree Hybrid"_. You can find the article by Ron Kohavi [online](https://www.aaai.org/Papers/KDD/1996/KDD96-033.pdf). The data used here consists of small changes to the original dataset, such as removing the `'fnlwgt'` feature and records with missing or ill-formatted entries.

## Models evaluated
Decision Trees, AdaBoost and Support Vector Machine. The evaluation criteria is a combination of model accuracy and training time. Finnaly AdaBoost is chosen with accuracy score 0.86
