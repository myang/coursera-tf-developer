## Sentiment in text
* IMDB comments positive or nagtive;
* Tokenize: map each word to numbers; OOV: Out of Vocabulary
* Sequencing: for each sentence, form the 2D array, one row for each sentences, one word number for each column;
## Word Embeddings
* create an Embedding layer
* for multiclassifier, don't forget to use activation "softmax" instead of "sigmoid" for the last Dense layer;
* for tokenizing labels, use Tokenizer(). Don't specify num_words or oov_token;
* for model.fit(), train/label data have to be in Numpy array;
