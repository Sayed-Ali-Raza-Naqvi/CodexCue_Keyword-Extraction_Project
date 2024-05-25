# Text Preprocessing and Keyword Extraction from Research Papers

## Overview
This project preprocesses text data from research papers and extracts keywords using TF-IDF (Term Frequency-Inverse Document Frequency). The keywords are intended to represent the most important terms in the documents. The process involves cleaning the text, tokenizing, stemming, removing stopwords, and then applying TF-IDF to identify significant terms.

## Files
- papers.csv: The CSV file containing the research papers data.
- count_vectorizer.pkl: A pickle file containing the trained CountVectorizer model.
- transformer.pkl: A pickle file containing the trained TfidfTransformer model.
- feature_names.pkl: A pickle file containing the feature names extracted from the CountVectorizer model.

## Dependencies
- Python 3.x
- Pandas
- NLTK
- Scikit-learn
- CSV
- Regex

## Code Description
The code consists of several components:
- Loading and cleaning data from the CSV file.
- Text preprocessing, including converting to lowercase, removing HTML tags and non-alphabet characters, tokenizing, removing stopwords, and applying stemming.
- TF-IDF transformation to compute the significance of terms.
- Keyword extraction from documents based on TF-IDF scores.
- Displaying extracted keywords along with the title and abstract of each document.
- Saving the trained models and feature names to pickle files for future use.

## Acknowledgments
- Artificial Intelligence (YouTube Channel)
