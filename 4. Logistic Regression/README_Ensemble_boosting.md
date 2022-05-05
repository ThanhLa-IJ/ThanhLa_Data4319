# Ensemble Boosting

Boosting is an ensemble technique that has the goal of creating a strong classifier from a number of weaker classifiers. AdaBoost is a boosting algorithm developed for binary classification and was the first to be truly successful. Learn AdaBoost is an effective way to understand boosting.

This technique is done through building a model from the training data, then subsequent models are created, trying to correct the errors from the first model. Models are added until the training set is perfectly predicted or the number of models reaches a maximum threshold. Models are generated one after another, the performance of the former will affect how the latter is built. After all models are built, predictions are made on the new data. This time, each model is weighted depending on its accuracy on the training data.