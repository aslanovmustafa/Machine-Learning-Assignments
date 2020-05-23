Text classification

 

Text classification is the process of assigning tags or categories to text according to its content. It’s one of the fundamental tasks in Natural Language Processing (NLP) with broad applications such as sentiment analysis, topic labeling, news classification spam detection, and etc.

You are given a data corpus (azeri_news.xlsx) of labeled Azerbaijani news articles. The labels identify the category of a given news article such as “dünya”, “idman”, “İqtisadiyyat”, “maraqlı”, “mədəniyyət”, “siyasət”.

Tasks:

- Extract features from news documents using Bag of Words (BOW) method (30%)
- Randomly split dataset into train and test sets. Train a Naïve Bayes classifier on training dataset.  (40%)
- Evaluate the performance of the model on the test set (30%):
    + Find the accuracy, Precision, Recall of the model
    + Construct confusion matrix
