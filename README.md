# TF-IDF from Scratch

This project demonstrates how to calculate TF-IDF (Term Frequency-Inverse Document Frequency) from scratch for a set of generated documents.

## Data

The documents used in this project are all generated.

## Data Processing

1. **Cleaning**: Removed any symbols or characters not relevant to the data.
2. **Normalization**: Converted all text to lowercase.
3. **Tokenization**: Split the text into individual words.
4. **Lemmatization or Stemming**: Returned each word to its root form.
5. **Stop Words Removal**: Removed common stop words from the text.

## Unique Words

Extracted the unique words from the processed data.

## TF-IDF Calculation

The final output is a feature vector for each document based on TF-IDF. The steps are as follows:

1. Calculate Term Frequency (TF) for each word in all documents.
2. Calculate Inverse Document Frequency (IDF) for each word.
3. Compute TF * IDF for each word.
4. Normalize the TF-IDF vectors (using sklearn equations).

