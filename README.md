# TEXT-Summarization-using-NLP

A Python-based text summarization tool that uses Natural Language Processing (NLP) techniques to generate concise summaries from input text.
Overview
This project implements an extractive text summarization approach using spaCy for natural language processing. It analyzes word frequencies and sentence scores to identify and extract the most significant sentences from a given text.
Requirements

Python 3.x
spaCy
spacy English language model (en_core_web_sm)

>> Usage
   The code processes text through the following steps:
   1.)Tokenization and preprocessing
   2.)Word frequency calculation
   3.)Sentence scoring
   4.)Summary generation
Features

Removes stopwords and punctuation
Calculates normalized word frequencies
Scores sentences based on word importance
Generates summaries of configurable length (default 30% of original text)

Implementation Details:

Text Processing

Uses spaCy for tokenization and sentence segmentation
Removes stopwords and punctuation
Normalizes word frequencies


Scoring Mechanism

Calculates word frequencies
Assigns scores to sentences based on word importance
Uses heapq for selecting top-scoring sentences
