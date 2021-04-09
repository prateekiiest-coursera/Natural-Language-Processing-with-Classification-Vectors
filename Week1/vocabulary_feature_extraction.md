## Vocabulary and Feature Extraction


### Learnings

- Learned a simple modular framework of how to convert words in list of tweets to numerical word embeddings by using a vocabulary dictionary.

- Through vocab. dictionary get the words which uniquely occur in all tweets.
- From them, for each tweet find the words that actually exists in the dictionary. Assign 1 if match or 0 otherwise.

- Learnt the concept of Sparse Representation i.e. a word embedding with too many zeros and few ones. Possible in cases where the vocabulary dictionary is quite extensive and our tweet only comprises only a few word from that dictionary.