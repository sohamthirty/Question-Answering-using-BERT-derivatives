# Question-Answering-using-BERT-derivatives

## Data
**[SQuAD 1.1 | Pranav Rajpurkar](https://rajpurkar.github.io/SQuAD-explorer/)**

## Overview
Question Answering Systems allow a user to express a question in natural language and get an immediate and brief response. It is an important task in the field of information retrieval and natural language processing (NLP). They enable us to properly use the huge amounts of information by helping in saving time and effort to scan the entire corpus. QA systems are found in search engines and phone conversational interfaces, and they’re good at answering simple snippets of information. The dataset being used in this project is the SQuAD1.1 which contains 100,000+ text answers to every question from a Wikipedia based reading passage.

## Problem Statement
The project aims to predict answers to the given set of questions with the help of embedding and transformer based models and evaluate their results.

## Tasks
- • Created a scalable QnA model by leveraging preprocessed Word2Vec, SIF embeddings on SQuAD v1.1 with 100K+ pairs
- • Achieved high accuracy of 81% EM and 84.5% F1-Score by implementing Distil-BERT-BERT ensemble transformer model


## Models
1. Embedding models: **Word2Vec, SIF**
2. Transformer models: **BERT, ALBERT, DISTILBERT**


## Results

### QnA Snippet
![image](https://github.com/sohamthirty/Question-Answering-using-BERT-derivatives/assets/56295513/935de381-7633-45d3-b597-340b00002a10)

### Metrics
![image](https://github.com/sohamthirty/Question-Answering-using-BERT-derivatives/assets/56295513/f382331b-340f-41bc-9281-d97805d9ef28)


## Conclusion
We used cosine similarity as metrics for embeddings model and EM and F1 score as metric for the other two categories. 
Our models performed quite well, with an EM score of above 84% for the BERT and ensemble models. 

In future, we would try to explore more efficient variants of BERT like ELECTRA and ROBERTa and explore top performing ensemble architectures like IE-Net which achieves accuracy of 90% with EM metrics.
