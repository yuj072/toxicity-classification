# Toxicity Classification

Project Type: Independent

# Motivation

Mathematics has always been interesting yet very abstract for me. That is why when I wanted to accomplish a project that is not so heavily rooted in theory, I always turn to Computer Science. However, through Natural Language Processing and Deep Learning, I found an unexpected intersection of these two fields when I enrolled in a Natural Language Processing class out of interest. As a Mathematics-Computer Science major, this interested me greatly, but I did not have any formal education in the field of Deep Learning. Thus, I took it upon myself to learn more about this field and a competition is a great way to start.


# Summary

Link to competition: https://www.kaggle.com/c/jigsaw-unintended-bias-in-toxicity-classification

The kernel parses the dataset (provided by Kaggle), builds a word embedding using GloVe and Fasttest crawl pretrained word embeddings and then concatenates the two word embedding matrices. Then it takes every comment inside of the dataset and then runs it through the model I designed. Lastly, it performs KFold Validation and all the predictions are averaged by dividing by the number of epochs.

# Results

This kernel obatined an accuracy of 92.133% (Given by Kaggle when I submitted my code into the competition).

# Ways to Improve

- Mapping abbreviations to their two-word counterparts (eg. can't -> can not)
- Clean up common misspellings.
- Take upper and lower case into account. (ThIs Is MoCkInG a StAtEmEnT)
