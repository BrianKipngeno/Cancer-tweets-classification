# Cancer-tweets-classification

Overview
This project uses text data to build a classification model to predict whether a tweet discusses cancer. The dataset contains tweets labeled as either talking about cancer ("yes") or not ("no"). We employ various machine learning models to solve this classification problem.

Dataset
The dataset is a TSV file and can be downloaded from this URL( https://bit.ly/3h2hDuw). It contains two columns:

text: The tweet content.
target: The label (yes/no).
Steps
Data Preprocessing:

Remove URLs, hashtags, and unnecessary characters.
Convert text to lowercase, remove stop words, and apply lemmatization.
Feature Engineering:

Text length, word count, part-of-speech tagging.
TF-IDF for word and character n-grams.
Modeling:

Trained multiple models including Logistic Regression, Decision Trees, SVM, and ensemble classifiers like Random Forest and Gradient Boosting.
Evaluation:

Accuracy, precision, recall, and F1-score were used for model performance evaluation.
Confusion matrices and classification reports were generated for insights.
Requirements
Python 3.x
Libraries: pandas, scikit-learn, nltk, textblob, seaborn, wordninja
Usage
Clone the repository.
Install the required libraries using pip install -r requirements.txt.
Run the notebook or script to train and test the models
