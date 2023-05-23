# IRTM Project
Data from
https://www.presidency.ucsb.edu/documents/app-categories/spoken-addresses-and-remarks/presidential/state-the-union-addresses?items_per_page=60


## Implementation

### Preprocessing:
Coreference handling
negation handling
pos tagging
tokenization 

### Named entity recognition
nltk chunking
BERT/transformers (pretrained with some fine tuning)

### Sentiment analysis
BERT/transformers (pretrained with some fine tuning)
(roberta)
SVM classifiers

### Topic extraction
https://huggingface.co/davanstrien/imdb_bertopic

simple clustering with K-NN
