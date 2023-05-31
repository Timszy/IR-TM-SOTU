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
nltk chunking Timo
BERT/transformers (pretrained with some fine tuning) Florent
https://huggingface.co/dslim/bert-base-NER Florent

### Sentiment analysis
BERT/transformers (pretrained with some fine tuning) Florent
(roberta)
TextBlob Timo
### Topic extraction
Unsupervised with:
LDA Timo
LSI Timo
NMF Timo
