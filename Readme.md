NAMED ENTITY RECOGNITION
=====================

### Bidirectional Encoder Representations from Transformers or BERT for short is a very popular NLP model from Google known for producing state-of-the-art results in a wide variety of NLP tasks.The importance of Natural Language Processing(NLP) is profound in the Artificial Intelligence domain. The most abundant data in the world today is in the form of texts and having a powerful text processing system is critical and is more than just a necessity.



A->
--------

  

### DATASET PREPARATION

*   Making the dataset input format which is suitable for BERT to perform.
*   Dataset will have id, data, label, category, tokens and split tokens.

B->
--------


### NER MODEL

*	Configuration
	BATCH_SIZES - These are batch sizes for each fold. For maximum speed, it is best to use the largest batch size your GPU or TPU memory allows.
	EPOCHS - These are maximum epochs. Note that each fold, the best epoch model is saved and used. So if epochs is too large, it won't matter. Consider early stopping in Callbacks.
	MODEL_CHECKPOINT - The name of the transformer model.

*	File and dataset handling
	Data cleaning, annotations and formatting has already been done, tokenized to seperate words, tagged using the IOB format and serialized using the Pandas df.to_json() function using the orient="table" parameter to a JSONL file.

*	Preprocessing Data - Tokenization
	Before we can feed those texts to our model, we need to preprocess them specifically for the pre-trained model that we are using. Even though we have already tokenized and split our words into a list, each model will have it's own further method of tokenization to match the dictionary for each specific model.

	This is done by a 🤗 Transformers Tokenizer which will (as the name indicates) tokenize the inputs (including converting the tokens to their corresponding IDs in the pretrained vocabulary) and put it in a format the model expects, as well as generate the other inputs that model requires.

*	Build Model
	Since all our tasks are about token classification, we use the AutoModelForTokenClassification class. Like with the tokenizer, the from_pretrained method will download and cache the model for us. The only thing we have to specify is the number of labels for our problem (which we can get from the features, as seen before).

*	Model Training

*	Model Prediction
