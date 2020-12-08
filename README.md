# Jeopardy Analysis

## Executive Summary
Jeopardy is a game that tests the ability of contestants to answer a wide variety of questions from all kinds of topics.

Preparing for a game of Jeopardy can take years and victory (or large prize money) is not a guarantee even then. This project is an attempt to help us use data science to prepare more effectively and give us a shot at Jeopardy glory.

This project uses regex to quickly clean, sort and search through the Jeopardy dataset, find commonalities and help calculate the significance of specific Jeopardy questions.

## Dependencies

Jupyter notebook is used and the code is written in Python 3.

The following are the different modules used in the project:
* Pandas
* Numpy
* Regex
* Scipy

## Results obtained
Sorting the rows into high - value and low - value rows does not yield any significant unique words. This means we can't get significant topics to focus on this way. We'll have to find another way to prepare for the game show.

## Possible Improvements

* Look for other ways to segment the questions.
* Look at the `Category` column and if there's a skewed distribution there, take advantage of that for a more expedient preparation.
* Apply NLP techniques to the questions
* Analyze the larger dataset and see if there's significant variance or fluctuation over time in the frequency of topics or questions asked on the show.
