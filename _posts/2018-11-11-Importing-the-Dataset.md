---
layout: post
title: Importing The Dataset.
---

### Steps For Importing the Dataset When Working With Jupyter Notebook.

1. Save the Jupyter Notebook File in the folder containing the dataset.

2. Best library to import the data set is **pandas**.So we're going to use pandas to import the data set.

## Question ) How to import Dataset using pandas?

#### Code:
{% highlight python %}
#Import Numpy.
import numpy as np
# Import Matplotlib.We will import a sub-library pyplot.
import matplotlib.pyplot as plt
#Import Pandas.
import pandas as pd
#Import the dataset.
df=pd.read_csv('NameOfDataSet.csv')
{% endhighlight %}

## Question ) What to do after importing the Dataset?
> After importing the dataset, we need to distinguish the matrix of features and the dependent variable vector.ie Divide the data in the independent variable matrix and the dependent vector.

**Consider the dataset**

![Dataset](/images/ImportingDataset/importdataset1.png)

##### Note:
  * In the Dataset we have three independent features.
    - Country
    - Age.
    - Salary .

  * And One Dependent Variable.
    - Purchased.

## Question ) How to distinguish dataset into independent matrix and dependent vector?
{% highlight python %}
#Assign the matrix of first three independent variables to X.
X= df.iloc[:, :-1].values
#Assign the dependent variable values to y.
y=df.iloc[:,3].values
{% endhighlight %}
[Reference to more examples accessing data with pandas](https://www.kaggle.com/sohier/tutorial-accessing-data-with-pandas/)

- Note:
  - Indexes in Python starts at zero.
