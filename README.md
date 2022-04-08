## ADS 509: Topic Modeling

Topic modeling is a fundamental text analysis technique since asking "What are these documents about?" is a fundamental question. In this assignment you will build a LDA topic model and an LSA topic model. You will compare the coherence of the two models and compare the resulting topic allocation. In this assignment we will work with the Brown University corpus in `nltk`. The documents are in categories already, so you can compare your models to the official classification.


1. Prepare the data for the `gensim` LDA modeling as in the example. 
1. Fit your model. Feel free to play around with the number of topics and 
the number of passes (and alpha, if you're feeling adventerous.) 
1. Estimate the most likely topic for your documents (or a subset of your
documents). 
1. The topic estimates come with probabilities. For each topic, show the 
single document that had the highest probability of being in that topic. 

## Instructions

1. Create a repository under your GitHub account from this template: https://github.com/37chandler/ads-tm-topic-modeling. Instructions can be found [here](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template). Make your repository public or add your instructor’s Github account as a [collaborator](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-github-user-account/managing-access-to-your-personal-repositories/inviting-collaborators-to-a-personal-repository).   
1. The notebook “Topic Models.ipynb” holds detailed instructions for the assignment. In that notebook you are asked to do the following: 
    
    * Calculate descriptive statistics on the two sets of lyrics and compare the results. 
    * Calculate TF-IDF matrices on the lyrics sets to identify the words that best identify the two artists. 
    * Tokenize your Twitter descriptions, keeping hashtags and emojis in your token set. The repeat the TF-IDF analysis on these two corpora.
    * Highlight one interesting differentiating feature between your two artists using either the lyrics data or the Twitter data or both. 
    * Build word clouds for all four corpora. 

1. Work through the notebook, performing the steps asked of you. Use and extend the code from the chapters of your textbook.

## Assignment Materials
  
* Group Comparison Repository
* (Optional) M1 Assignment Data.zip

Deliverables:

* When you have finished your code, print your notebook as a PDF and upload this document to Blackboard. 
* Commit your code and push the changes to GitHub so your instructor has access to the ipynb notebook file and any other code you create. 
