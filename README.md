# Turkish Author Classification Project

## Overview

This project aims to build a classification model for Turkish columnists based on their writings. The model leverages natural language processing (NLP) techniques to preprocess and analyze the text data, ultimately classifying the author of a given text. The goal is to explore patterns and writing styles specific to each author.

## Features

- **Text Preprocessing:**
  - Special character removal
  - HTML tag removal
  - Lowercase conversion
  - Stopword removal
  - Lemmatization
  - Stemming

- **Classification Model:**
  - Utilizes Bag of Words representation
  - Logistic regression for author classification

- **Zemberek Integration:**
  - Turkish language processing with Zemberek for tokenization and lemmatization.

## Technologies Used

- Python
- Pandas
- NLTK
- Zemberek
- Scikit-learn

## Getting Started

1. Clone the repository.
2. Install the required dependencies using `pip install -r`.
3. Preprocess your dataset by following the instructions in the preprocessing notebook.
4. Train the classification model using the Bag of Words approach.

## Usage

- After preprocessing, use the classification model to predict authors for given texts.
- Explore the Jupyter notebooks for detailed steps and visualizations.

