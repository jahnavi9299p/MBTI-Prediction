# MBTI Personality Prediction
# Speckbit Capstone Project 2

## Description:
The Myers Briggs Type Indicator (or MBTI for short) is a personality type system that divides everyone into 16 distinct personality types across 4 axis:

    Introversion (I) – Extroversion (E)
    Intuition (N) – Sensing (S)
    Thinking (T) – Feeling (F)
    Judging (J) – Perceiving (P)

So for example, someone who prefers introversion, intuition, thinking and perceiving would be labelled an INTP in the MBTI system, and there are lots of personality based components that would model or describe this person’s preferences or behaviour based on the label.

It is one of, if not the, the most popular personality test in the world. It is used in businesses, online, for fun, for research and lots more. A simple google search reveals all of the different ways the test has been used over time. It’s safe to say that this test is still very relevant in the world in terms of its use.

From scientific or psychological perspective it is based on the work done on cognitive functions by Carl Jung i.e. Jungian Typology. This was a model of 8 distinct functions, thought processes or ways of thinking that were suggested to be present in the mind. Later this work was transformed into several different personality systems to make it more accessible, the most popular of which is of course the MBTI.

Despite its validity in question due to its unreliability in experiments surrounding it, it is a very useful tool in a lot of areas, and the purpose of this dataset is to help see if any patterns can be detected in specific types and their style of writing, which overall explores the validity of the test in analysing, predicting or categorising behaviour.

## Content

This dataset contains over 8600 rows of data, on each row is a person’s collection of tweets.
The tweets in the collection are to be separately identified by '|||'.
The no. of tweets in a collection range from 35 to 50 over the dataset.
The target is to predict overall mbti personality. 

## Acknowledgements
The dataset is downloaded from Kaggle at - https://www.kaggle.com/datasnaek/mbti-type .
This data was collected through the PersonalityCafe forum, as it provides a large selection of people and their MBTI personality type, as well as what they have written.

## Installation:
The to get started with Jupyter Notebook is by installing Anaconda.
To get Anaconda, simply:
Download the latest version of Anaconda for Python 3 (ignore Python 2.7) from the link
https://repo.anaconda.com/archive/ .
Install Anaconda by following the instructions on the download page and/or in the executable.
If you are a more advanced user with Python already installed and prefer to manage your packages manually, you can just use pip: *pip3 install jupyter*
However there are necessary packages that are needed to be installed explicitly such as nltk( after installing which numpy must be installed again).
To download the ipynb file from GitHub-
* Click on Raw.
* Then, press ctrl+s to save it as .ipynb .
* Open jupyter notebook.
* Go to location where you saved .ipynb file.
* Open file, you will see the code.


## Usage:
This was a beginner's attempt at Machine Learning hence the excitement to explore NLP.
After observing from the collection of tweets it is intuitively decided to perform Neural Networks.
In future this can be developed by use of machine learning to evaluate the MBTIs validity and ability to predict language styles and behaviour online.
