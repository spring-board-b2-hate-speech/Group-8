# Hate Speech Detection

This project focuses on detecting hate speech in text data using various natural language processing (NLP) techniques. The key tasks include tokenizing the text and generating embeddings using TF-IDF and Word2Vec. This README provides an overview of the project and instructions for running the code.


## Tokenization

Tokenization is the process of splitting text into individual words or tokens. This project uses several tokenization techniques to handle the text data.

### Methods Used

1. **NLTK Tokenization**: A popular NLP library that provides a simple and efficient way to tokenize text.


## Embedding Technique

In this project, we employed the Word2Vec embedding technique to convert textual data into numerical vectors that can be utilized by machine learning models. Word2Vec is a popular method that creates word embeddings by training a shallow neural network on a large corpus of text. It captures semantic relationships between words by placing similar words close to each other in the vector space.

## Library Used
To implement Word2Vec, we utilized the gensim library, which provides an efficient and easy-to-use interface for training and using Word2Vec models. gensim is a robust library for topic modeling and document similarity analysis, and it is widely used in the NLP community for its scalability and performance.
