# Problem Statement 
Classification of wine quality as good or bad based on chemical composition as opposed to the classical note based approached.
## Dataset

The dataset used is the https://www.kaggle.com/uciml/red-wine-quality-cortez-et-al-2009 from Kaggle.

The 2 class labels are:
<br>

**1. Good Quality:** Given wine belong to good quality wine
<br>
**2. Bad Quality:** Given wine belong to bad quality wine


## Model Used
 
A Random Forest Classifier was used for this project 
The core unit of random forest classifiers is the decision tree. The decision tree is a hierarchical structure that is built using the features (or the independent variables) of a data set. Each node of the decision tree is split according to a measure associated with a subset of the features. The random forest is a collection of decision trees that are associated with a set of bootstrap samples that are generated from the original data set. The nodes are split based on the entropy (or Gini index) of a selected subset of the features. The subsets that are created from the original data set, using bootstrapping, are of the same size as the original data set. 

## Future Work
In future iterations, we can make a database of different wines and their batches and use them as benchmarks, as well as predicting perfect mixture of elements to make a good quality wine.
