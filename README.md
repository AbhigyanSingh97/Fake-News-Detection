# Fake-News-Detection

Description : Worked with a dataset containing of 20,000 news datas approximately.



Language: Python



Approach: Data consisted of 5 columns(id,author,title,text,label), in which the title and author and text was combined into a single column named total,and the rest were dropped.

The newly created column(total) had preprocessing done on it.
1.tokenization
2.removal of stopwords
3.lemmatization

For Logistic Rgression and MultinomialNB models Count vectorizer was done and on the output of it Tfidf Transformation was done.

For LSTM and GRU models the input data was one hot encoded and the data was padded with pre padding of 30.



Algorithm used: Logistic Regression, MultinomialNB, LSTM and GRU.
