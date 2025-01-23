# Fake-News-Detection
This project is a binary classification task to identify whether a piece of news is real or fake. Using machine learning techniques, the project processes text data and builds classification models to accurately predict the news class.

Key Features:
Data Preprocessing: Cleans the text data by removing unnecessary characters, lowercasing, stemming, and removing stopwords.
Feature Extraction: Converts text into numerical vectors using TF-IDF Vectorization.
Model Training: Trains machine learning models like Logistic Regression and Decision Tree Classifier for classification.
Evaluation: Compares models using metrics like accuracy, precision, recall, F1-score, and confusion matrix.

Project Workflow:
Data Cleaning:
Drop irrelevant columns (title, date, subject) and missing values.
Shuffle the dataset for unbiased splitting.

Text Preprocessing:
Remove special characters and punctuation.
Convert text to lowercase.
Tokenize text and remove stopwords.
Apply stemming to normalize words.

Split Data:
Divide data into training (75%) and testing (25%) sets.
Feature Extraction:
Transform text into numerical features using TF-IDF Vectorization.

Model Training:
Train models like Logistic Regression and Decision Tree Classifier.
Evaluate their performance using accuracy and classification reports.

Visualization:
Visualize confusion matrix results for better interpretability.
