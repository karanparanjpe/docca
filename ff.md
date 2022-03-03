LINE CLASSIFICATION
=====================

### Bidirectional Encoder Representations from Transformers or BERT for short is a very popular NLP model from Google known for producing state-of-the-art results in a wide variety of NLP tasks.

###The importance of Natural Language Processing(NLP) is profound in the Artificial Intelligence domain. The most abundant data in the world today is in the form of texts and having a powerful text processing system is critical and is more than just a necessity.

A->
--------

  

### DATASET PREPARATION

*   Making the dataset input format which is suitable for BERT to perform.
*   Dataset will have id, data, label, category, tokens and split tokens.

B->
--------


### LC MODEL
THE CATEGORIES ARE LABELLED AS FOLLOWS:
CATEGORIES : NO_LABEL:0 PERSONAL:1 EDUCATION:2 WORK_EXPERIENCE:3 SKILLS:4

BERT model accept only a specific type of input and the datasets are usually structured to have have the following four features:

guid : A unique id that represents an observation.
text_a : The text we need to classify into given categories
text_b: It is used when we're training a model to understand the relationship between sentences and it does not apply for classification problems.
label: It consists of the labels or classes or categories that a given text belongs to.

We will be using bert_uncased_L-12_H-768_A-12/1 model.We will be using the vocab.txt file in the model to map the words in the dataset to indexes. Also the loaded BERT model is trained on uncased/lowercase data and hence the data we feed to train the model should also be of lowercase.
