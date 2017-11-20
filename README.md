# EEG sleep stage classification

The goal is to classify brain electroencephalograms in 5 categories of sleep.

This work is motivated by two reasons, using CNN on one-dimensional signals for
classification task and comparing its performance to hand-tuned feature
engineering. No feature engineering is done and raw signals is fed into the CNN.

The architecture is built using TensorFlow.

In a previous work not included in this repository, hand-tuned features
combined with stacking of multiple models, reached 79% of cross-validated
accuracy on the same dataset (svm, gradient boosting, regression).
