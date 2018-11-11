---
layout: post
title: Importing the Libraries
---

After getting the dateset,We need to know how to process any data before applying machine learning algorithms.

### First step in data processing includes :-
> How to import the Libraries ?

## Question ) What is a Library?
> A library is a tool that you can use to do a specific job, i.e  you just need to give some instructions, then the library will do the work for you and return some outputs.

## Question ) What's cool about these Libraries?
> We will mainly use libraries during this course of building Machine Learning models as it makes the process efficient as possible.

## Question ) What are the essential Libraries we will use during Data Preprocessing?
> There are three essential libraries that are mostly used in Machine Learning :
#### Numpy :
This library contains mathematical tools and basically this is the library that we need to include to perform any kind of maths in our code.
####  Matplotlib :
This library that will help us draw nice charts and graphics.Whenever we want to trace something in Python,we use Matplotlib.
It contains very intuitive and useful tools.
#### Pandas :
Panda library is actually the best library for importing datasets and managing datasets.We will see that it is really intuitive as well.And we'll spend most of the time importing our data sets, and sometimes we use it to manage them.

#### Code:
{% highlight python %}
#Import Numpy.
import numpy as np
# Import Matplotlib.We will import a sub-library pyplot.
import matplotlib.pyplot as plt
#Import Pandas.
import pandas as pd
{% endhighlight %}

- Note:
  - To import a library into python we use **import** keyword.
  - To use these libraries faster while coding we can make a shortcut using **as** keyword.
