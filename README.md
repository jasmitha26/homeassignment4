# Homeassignment4
# README - Home Assignment 4 (Neural Networks and Deep Learning)

## Student Information
*Name:* Jamitha Nalla
*Course:* CS5720 Neural Networks and Deep Learning  
*Semester:* Spring 2025  
*University:* University of Central Missouri  
*Student ID :* 700779225
*Submission Date:* 4/21/2025

## 🔧 Description

This repo contains solutions for the following NLP and Attention-related tasks:

1. *NLP Preprocessing* (Tokenization, Stopword Removal, Stemming)
2. *Named Entity Recognition* using SpaCy
3. *Scaled Dot-Product Attention* implementation from scratch
4. *Sentiment Analysis* using HuggingFace Transformers

## 🚀 Run Instructions

- All scripts are written in Python 3
- Install dependencies using:

```bash
pip install nltk spacy transformers
python -m nltk.downloader punkt stopwords
python -m spacy download en_core_web_sm




# Q1) NLP Preprocessing Pipeline
## Description:
This project demonstrates a simple NLP preprocessing pipeline in Python using the NLTK library. The pipeline performs the following steps:

1. *Tokenization* - Splits a sentence into individual words and punctuation.
2. *Stopword Removal* - Removes common English stopwords like "the", "in", "are".
3. *Stemming* - Reduces words to their root forms using the Porter Stemmer.

## Sample Input Sentence:
```text
"NLP techniques are used in virtual assistants like Alexa and Siri."

# Named Entity Recognition (NER) with spaCy

## Student Details:
- *Name*: Lokesh Reddy Siripireddy
## Project Description:
This project demonstrates how to perform Named Entity Recognition (NER) using the spaCy library in Python. The script analyzes a sentence to identify named entities such as people, places, dates, and more. It prints the entity text, its label, and the character positions within the input sentence.

## Tools Used:
- Python 3.x
- spaCy library (en_core_web_sm model)

## Installation:
To install the required dependencies, run the following:

```bash
pip install spacy
python -m spacy download en_core_web_sm


# Q2)Named Entity Recognition (NER) with spaCy
## Project Description:
This project demonstrates how to perform Named Entity Recognition (NER) using the spaCy library in Python. The script analyzes a sentence to identify named entities such as people, places, dates, and more. It prints the entity text, its label, and the character positions within the input sentence.

## Tools Used:
- Python 3.x
- spaCy library (en_core_web_sm model)

## Installation:
To install the required dependencies, run the following:

```bash
pip install spacy
python -m spacy download en_core_web_sm


 

#Q3)Scaled Dot-Product Attention Implementation
## Description:
This project implements the *Scaled Dot-Product Attention* mechanism, a core component of the Transformer architecture used in NLP and deep learning. It follows these steps:

1. Computes the dot product of the *Query (Q)* and the transpose of *Key (K)*.
2. Scales the result by dividing by the square root of the key dimension.
3. Applies the softmax function to obtain attention weights.
4. Multiplies the attention weights by the *Value (V)* matrix to get the final output.

## Libraries Used:
- numpy
- scipy.special (for softmax)

## Input:
```python
Q = np.array([[1, 0, 1, 0], [0, 1, 0, 1]])
K = np.array([[1, 0, 1, 0], [0, 1, 0, 1]])
V = np.array([[1, 2, 3, 4], [5, 6, 7, 8]])

#Q4) Sentiment Analysis Using HuggingFace Transformers


## Description:
This project uses the transformers library by HuggingFace to perform sentiment analysis. It utilizes a pre-trained pipeline to determine whether a sentence expresses a positive or negative sentiment.

## Tools Used:
- Python 3.x
- HuggingFace Transformers library

## Installation:
Install the necessary library using pip:

```bash
pip install transformers




