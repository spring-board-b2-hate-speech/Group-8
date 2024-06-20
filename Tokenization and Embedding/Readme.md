
## Tokenization

Tokenization is the process of splitting text into individual words or tokens. This project uses several tokenization techniques to handle the text data.

### Methods Used

1. **NLTK Tokenization**: A popular NLP library that provides a simple and efficient way to tokenize text.


## Embedding Technique

WordToVec:
In this project, we employed the Word2Vec embedding technique to convert textual data into numerical vectors that can be utilized by machine learning models. Word2Vec is a popular method that creates word embeddings by training a shallow neural network on a large corpus of text. It captures semantic relationships between words by placing similar words close to each other in the vector space.

Term Frequency (TF):
Term Frequency (TF) measures the frequency of a word in a document relative to the total number of words in that document. It is a simple way to convert text into numerical data that can be fed into machine learning models. Each document is represented as a vector, with each element in the vector representing the count of a word in the document.

TF-IDF (Term Frequency-Inverse Document Frequency)
TF-IDF is an extension of Term Frequency that adjusts for the fact that some words appear more frequently in general. It combines Term Frequency (TF) and Inverse Document Frequency (IDF). IDF reduces the weight of words that appear frequently across many documents and increases the weight of words that are rare. The TF-IDF value increases proportionally to the number of times a word appears in the document but is offset by the number of documents in the corpus that contain the word.


## Library Used
To implement Word2Vec, we utilized the gensim library and scikitlearn, which provides an efficient and easy-to-use interface for training and using Word2Vec models. gensim is a robust library for topic modeling and document similarity analysis, and it is widely used in the NLP community for its scalability and performance.

# Conclusion

### Based on these metrics, TF-IDF embeddings demonstrated the best performance with the SVM model. TF-IDF provided a balanced and effective representation of the textual data, leading to higher accuracy and better overall performance metrics compared to Term Frequency and Word2Vec embeddings. Therefore, we decided on using TF-IDF embeddings for this hate speech detection project.
