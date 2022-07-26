# Glove_Model
The GloVe model is trained on the non-zero entries of a global word-word co-occurrence matrix, which tabulates how frequently words co-occur with one another in a given corpus.
Populating this matrix requires a single pass through the entire corpus to collect the statistics.
<br><br>
Is GloVe better than word2vec?<br>
In the practice, Word2Vec employs negative sampling by converting the softmax function as the sigmoid function. This conversion results in cone-shaped clusters of the words in the vector space while GloVe's word vectors are more discrete in the space which makes the word2vec faster in the computation than the GloVe.
