# NLP_project_1
Predicting fake news using word embeddings and comparing their performance
We have fake and real news dataset. Link to the dataset: "https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset?select=Fake.csv".
The dataset contains the following columns: "title","text","subject","date". There are two seperate dataset for fake and real news.
We take 500 rows from both dataset and then combine them to form a single dataset with additional column conveying whether news is real or fake.
Then we use word embedding models to create vector from the available news text column.
The word embeddings used are: word2vec, BERT-base, BERT-Large and AlBERT.
After creating the vectors from these word embedding models, we train a binary classification model to predict whether news is real or fake.
Our novel application with this programming assignment is that we are comparing various word embedding models on this specific task of fake news prediction.
Word embeddings play a huge role in predicting the label. The vector produced includes various features in numerical form which differs from model to model.
We try to figure out which word embedding model creates the best vectors assisting in predicting fake news.
