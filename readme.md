# Overview

Activity prediction for chemical compounds using Random Forests.  

# Dataset 

[Tox21 data](https://tripod.nih.gov/tox21/challenge/) was released as part of a challenge in data analysis by to reveal how well they can predict compounds' interference in biochemical pathways using only chemical structure data. In this project we will use a subset of the data that consists of 19,125 chemical compounds represented bySMILES together with their activity label (0 = inactive, 1 =active).

Note: the dataset is included in the data folder.

# Model

A Random Forest with 100 trees.

It was trained from scratch on the training data using [scikit-learn](https://scikit-learn.org/).

# Metrics

The model achieved 97% accuracy on the validation set with AUC score of 81% (random 20% subset of the training dataset).