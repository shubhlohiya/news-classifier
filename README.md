# Naive Bayes Classifier for News Articles

This repository contains code for programming assignment 2 of [CS 635, Autumn 2021](https://www.cse.iitb.ac.in/~soumen/teach/2013.2A.CS635) at IIT Bombay. 

The dataset used is [20 Newsgroups Data Set](http://qwone.com/~jason/20Newsgroups/) and the split is [**20news-bydate**](http://qwone.com/~jason/20Newsgroups/20news-bydate.tar.gz). 

News documents have been represented using the *Bag of Words* approach (both binary and count BoW have been considered). For the Naive Bayes Classifier, the user can choose from the *multinomial* and *poisson* models for modelling the generative process for the News Documents.

### Steps to run the code:

* Download the dataset and place the extracted data folder in the root directory of this repository
* Install the dependencies
    ```
    pip install tqdm numpy spacy jupyter
    ```
* Open the notebook and run the cells
    ```
    jupyter notebook code/news_classification.ipynb
    ```