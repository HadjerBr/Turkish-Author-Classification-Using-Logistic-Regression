Overview

This project aims to build a classification model for Turkish columnists based on their writings. The model leverages natural language processing (NLP) techniques to preprocess and analyze the text data, ultimately classifying the author of a given text. The goal is to explore patterns and writing styles specific to each author.
Features

    Text Preprocessing: Special character removal, HTML tag removal, lowercase conversion, stopword removal, lemmatization, and stemming.
    Classification Model: Utilizes Bag of Words representation and logistic regression for author classification.
    Zemberek Integration: Turkish language processing with Zemberek for tokenization and lemmatization.

Technologies Used

    Python
    Pandas
    NLTK
    Zemberek
    Scikit-learn

Getting Started

    Clone the repository.
    Install the required dependencies using pip install -r requirements.txt.
    Preprocess your dataset by following the instructions in the preprocessing notebook.
    Train the classification model using the Bag of Words approach.

Usage

    After preprocessing, use the classification model to predict authors for given texts.
    Explore the Jupyter notebooks for detailed steps and visualizations.
