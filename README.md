# Spam Classification Project

## Overview

The "Spam Classification Project" aims to classify text messages as either spam or non-spam (ham) using Natural Language Processing (NLP) techniques.

## Files

* spam.csv: The dataset file containing text messages and their corresponding labels.
* spam_classifier.ipynb: Jupyter notebook with code for data cleaning, preprocessing, model building, evaluation, and deployment.


## Usage
* Clone the GitHub repository:

git clone https://github.com/your_username/Spam-Classification-Project.git

* Install required dependencies:

pip install pandas nltk scikit-learn

* Run the spam_classifier.ipynb notebook to build and evaluate the model.

* Run "streamlit run app.py" to run the website

## Model Deployment

The best-performing model is saved using Pickle to model.pkl.

The TF-IDF vectorizer used for text preprocessing is saved to vectorizer.pkl.
