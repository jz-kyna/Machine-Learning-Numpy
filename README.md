# Machine-Learning-Tutorial
### *WARNING, this README got heavy GIF files to load.*

Code Machine learning models from scratch. Trying to implement some optimizers and models from scratch. Will try to update over time.

1. [Evolution Strategies Optimizer](deep-evolution-entropy)
2. [Deep feed-forward on (Gradient Descent, Momentum Gradient Descent, Nesterov Momentum, Adagrad, RMSprop, ADAM)](deep-feed-forward)
3. [Vanilla Recurrent Neural Network on (Gradient Descent, Momentum Gradient Descent, Nesterov Momentum, Adagrad, RMSprop, ADAM)](vanilla-rnn)
4. [Long-Short-Term-Memory Recurrent Neural Network on (Gradient Descent, Momentum Gradient Descent, Nesterov Momentum, Adagrad, RMSprop, ADAM)](lstm-rnn)
5. [Deep Learning Regularization (L1, L2, L1-L2)](deep-learning-regularization)
6. [Deep Learning Dropout](deep-learning-dropout)
7. [Deep Learning Batch Normalization](deep-learning-batchnormalization)
8. [Regressions (linear, polynomial, lasso, ridge, elasticnet)](regression)
9. [K-mean](k-mean)
10. [TSNE (original TSNE, Adaptive Momentum TSNE)](tsne)
11. [Principal Component Analysis](pca)
12. [Naive Bayes on TF*IDF Twitter dataset (gaussian, multinomial)](bayes-tfidf)
13. [Gradient Visualization for evolution based and derivative based (MSE, RMSE, MAE)](gradient-visualization)
14. [K-Nearest Neighbors](K-nearest-neighbors)
15. [Decision Tree (Classification Tree, Regression Tree)](decision-tree)
16. [Gradient Boosting (Classification Tree, Regression Tree)](gradient-boosting)
17. [Bagging (Classification Tree, Regression Tree)](bagging)
18. [Random Forest (Classification Tree, Regression Tree)](random-forest)
19. [Adaboost (Classification)](adaboost)

*Some of results are not good because of softmax and cross entropy functions I code.*
*If found any error on my chain-rules, feel free to branch*

## Gradient of Mean Square Error
Gradient based on evolution strategies

<img src="results/gradient-evolution.png" width="50%">
Gradient based on gradient descent

<img src="results/gradient-descent.png" width="50%">
</div>

## TSNE on Iris
<img src="tsne/animation-tsne-iris.gif" width="50%">

<img src="tsne/animation-tsne-perplexity-iris.gif" width="50%">

## Iris Data-set
### Evolution strategies
<img src="results/animation-evolution-iris.gif" width="50%">

### gradient descent
<img src="results/animation-gradientdescent-iris.gif" width="50%">

### momentum gradient descent
<img src="results/animation-momentum-gradientdescent-iris.gif" width="50%">

### nesterov momentum
<img src="results/animation-nesterov-gradientdescent-iris.gif" width="50%">

### adagrad
<img src="results/animation-adagrad-gradientdescent-iris.gif" width="50%">

### rmsprop
<img src="results/animation-rmsprop-gradientdescent-iris.gif" width="50%">

### adam
<img src="results/animation-adam-gradientdescent-iris.gif" width="50%">

## Comparison MSE gradient between models
<img src="results/mse-gradient.png" width="50%">
