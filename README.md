• Data: document are all generated

• Processing on data:
  1. I cleaned the data from each symbol or character doesn’t contain to the data.
  2. Normalization: put all the data to lower case
  3. Tokenization: split the data to words
  4. Lemmatization or Stemming: returned each word to origin.
  5. Stop words: removed stop words from the data.
     
• Unique words: - Got the unique words from the data.

• TFIDF: the output gets feature vector for each document.
  1. Got TF for each word for all documents.
  2. Got IDF for each word.
  3. Multiplied TF * IDF
4. Got Normalized TFIDF
I used (sklearn) equations.
