## one hot encoding

### Advantages
- Easy to implement {SLearmpmejptemcpder}
- Captures the presence or absence of a word

### Disadvantages
- Sparse metrix -> leads to overfitting
- High dimensional data
- ML algorithm need fixed size but here it is not a fixed size
- NO semantic meaning is getting captured
- Out of vocabulary (oov) words are not handled


## Bag of Words (BoW)

### Advantages
- Easy to implement
- Fixed sized vectors -> help to ML algorithms
- Captures the presence or absence of a word

### Disadvantages
- Sparse metrix -> leads to overfitting
- ordering of the word is getting changed
- NO semantic meaning is getting captured
- Out of vocabulary (oov) words are not handled

## TF-IDF (Term Frequency-Inverse Document Frequency)

### Advantages
- Easy to implement
- Fixed sized vectors -> help to ML algorithms
- Captures the presence or absence of a word

### Disadvantages
- Sparse metrix -> leads to overfitting
- ordering of the word is getting changed
- NO semantic meaning is getting captured
- Out of vocabulary (oov) words are not handled

<!--
Source - https://stackoverflow.com/a/52003495
Posted by Roman Vogt, modified by community. See post 'Timeline' for change history
Retrieved 2026-04-23, License - CC BY-SA 4.0
-->

![TF-IDF](../images/TF-IDF.png)

## Word Embeddings
In natural language processing, word embeddings are a type of word representation for text analysis, typically inthe form of a real-valued vector that encodes the meaning of the word in a way that the words that are closer in the vector space are expeced to be similar in meaning