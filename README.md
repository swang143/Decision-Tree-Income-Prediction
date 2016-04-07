# Decision-Tree-Income-Prediction

We'll look at the individual income data from cencus. It contains information about individual's marital status, age, type of work and so on. What we want to predict is, whether they make less than or equal to 50k per year or more than 50k per year.

Decision tree algorithm is a supervised learning algorithm. We first construct the tree with historical data and then use it to predict on new data. The reason why we choose decision tree algorithm is that it can pick up the nonlinear relationship between variables in data set that linear regression cannot. 

The disadvantage of decision tree algorithm is that decision trees overfit when they have too much depth, and make overly complex rules that match the training data, but aren't able to generalize well to new data. A good way to reduce decision tree overfitting is random forests. Therefore, we will also use random forests to solve this problem later in the Random-Forests-Income-Prediction Repository.
