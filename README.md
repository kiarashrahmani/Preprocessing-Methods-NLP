# Preprocessing-Methods-NLP

## Introduction
This repository contains Python code for various text preprocessing techniques in Natural Language Processing (NLP). Text preprocessing is a crucial step in NLP, involving tasks such as tokenization, normalization, sentence boundary detection, stemming, part of speech tagging, named entity recognition, and anaphora resolution. These techniques are essential for preparing textual data for further analysis and modeling.

## Contents

### 1. Tokenization
Tokenization is the process of breaking text into individual words or tokens. In this project, the NLTK library is used for tokenization. The code demonstrates how to read text from local files and tokenize it using NLTK's word tokenizer.

### 2. Normalization
Normalization involves transforming tokens into a canonical form, making them uniform for analysis. This project covers two normalization techniques:
- **Stop Words Removal**: Common and non-meaningful words (stop words) are removed from the text to focus on semantically meaningful words.
- **Lemmatization**: Words are reduced to their base or root form, improving analysis accuracy.

### 3. Sentence Boundary Detection
Sentence boundary detection, or sentence segmentation, involves identifying sentence boundaries within a text. This project uses NLTK's sentence tokenizer to split the text into individual sentences.

### 4. Stemming
Stemming is the process of reducing words to their root form. This code demonstrates stemming using the Porter Stemmer algorithm from NLTK.

### 5. Part of Speech (POS) Tagging
POS tagging assigns a grammatical category (noun, verb, etc.) to each word in a sentence. This repository showcases how to perform POS tagging using NLTK.

### 6. Named Entity Recognition (NER)
NER involves identifying and classifying named entities (names, locations, etc.) within text. This project demonstrates NER using NLTK's named entity chunker.

### 7. Anaphora Resolution
Anaphora resolution is the task of connecting pronouns to their antecedents in a text. The code includes an example of resolving pronouns like "it" to their correct entities.

## Requirements
- Python 3.x
- NLTK library

## Usage
1. Clone the repository: `git clone https://github.com/kiarashrahmani/Preprocessing-Methods-NLP`
2. Install the required libraries: `pip install nltk`
3. Run the Python scripts for specific preprocessing tasks.

Feel free to explore, modify, and integrate these preprocessing techniques into your NLP projects! If you find this repository helpful, don't forget to star it. 

