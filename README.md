# Wine Quality prediction using Random Forest

<a href="https://colab.research.google.com/github/NeonRio/RedWineForest/blob/main/Red_Wine_qualitity_prediction.ipynb"><img data-canonical-src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab" src="https://camo.githubusercontent.com/84f0493939e0c4de4e6dbe113251b4bfb5353e57134ffd9fcab6b8714514d4d1/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667"></a>
<br />
This is red wine quality predictor using RandomForest ensemble machine learning model with Python.
<br />
Random forests or random decision forests is an ensemble learning method for classification, regression and other tasks that operates by constructing a multitude of decision trees at training time. For classification tasks, the output of the random forest is the class selected by most trees. For regression tasks, the mean or average prediction of the individual trees is returned. Random decision forests correct for decision trees' habit of overfitting to their training set. Random forests generally outperform decision trees, but their accuracy is lower than gradient boosted trees. However, data characteristics can affect their performance.

It has gained much popularity and attention recently as the algorithm of choice for many winning teams of machine learning competitions.

<img src="https://www.tibco.com/sites/tibco/files/media_entity/2021-05/random-forest-diagram.svg" width="70%"/>

### Dataset
<bold>About the dataset</bold>
<br />
This datasets is related to red variants of the Portuguese "Vinho Verde" wine. For more details, consult the reference [Cortez et al., 2009]. Due to privacy and logistic issues, only physicochemical (inputs) and sensory (the output) variables are available (e.g. there is no data about grape types, wine brand, wine selling price, etc.).

The datasets can be viewed as classification or regression tasks. The classes are ordered and not balanced (e.g. there are much more normal wines than excellent or poor ones).

This dataset is also available from the UCI machine learning repository, https://archive.ics.uci.edu/ml/datasets/wine+quality , I just shared it to kaggle for convenience. (If I am mistaken and the public license type disallowed me from doing so, I will take this down if requested.)

Content


For more information, read [Cortez et al., 2009].
Input variables (based on physicochemical tests):

1 - fixed acidity

2 - volatile acidity

3 - citric acid

4 - residual sugar

5 - chlorides

6 - free sulfur dioxide

7 - total sulfur dioxide

8 - density

9 - pH

10 - sulphates

11 - alcohol

Output variable (based on sensory data):

12 - quality (score between 0 and 10) 

### References
<hr>
<li><a href="https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009">
    https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009</a>
</li>
<li><a href="https://www.youtube.com/watch?v=v6VJ2RO66Ag">
    https://www.youtube.com/watch?v=v6VJ2RO66Ag</a>
</li>
<li><a href="https://towardsdatascience.com/understanding-random-forest-58381e0602d2">
    https://towardsdatascience.com/understanding-random-forest-58381e0602d2</a>
</li>
<li><a href="https://en.wikipedia.org/wiki/Random_forest">
    https://en.wikipedia.org/wiki/Random_forest</a>
</li>
