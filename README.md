FAKE NEWS DETECTION PROJECT
This project builds a machine-learning model that classifies news articles as Fake or Real using Natural Language Processing (NLP). The dataset contains labeled news articles, and after cleaning and preprocessing the text, TF-IDF features are extracted and used to train multiple ML models.
The final tuned model (SVM) achieves high accuracy and reliably distinguishes fake news from real news based on textual patterns.

FEATURES -
Text cleaning and preprocessing
TF-IDF feature extraction
Training & evaluation of ML models
Hyperparameter tuning
Confusion matrix & accuracy results

DATASET -
https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset?resource=download&select=True.csv
Uses two files:
Fake.csv
True.csv
Both are combined and labeled for binary classification.

MODEL PERFORMANCE -
Several machine-learning models were tested, including Logistic Regression, Naive Bayes, Random Forest, and SVM. After evaluation, the SVM model delivered the strongest performance, showing high accuracy and consistent classification results across both training and testing data.

PROJECT OUTCOME -
The final system is able to detect fake news with strong reliability by analyzing textual patterns. The project demonstrates how NLP and supervised learning can be applied effectively to a real-world problem, showcasing both model-building and analytical skills.
