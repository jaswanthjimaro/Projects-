Spam Detection System
This Python script implements a Spam Detection System using Natural Language Processing (NLP) techniques and machine learning algorithms. The system reads a dataset containing SMS messages labeled as spam or ham (non-spam), preprocesses the data, and trains two classification models: Logistic Regression and Random Forest.

Dataset
The dataset used for training and testing the models is provided in the file Dataset.csv. It contains SMS messages labeled as "spam" or "ham".

Preprocessing
The preprocessing steps include handling missing values, label encoding, and cleaning text data. Text data is cleaned by converting to lowercase and removing non-alphanumeric characters.

Classification Models
Two classification models are trained:

Logistic Regression
Random Forest
Evaluation
Model performance is evaluated using accuracy metrics and classification reports.

Prediction
The script allows users to input messages for spam or ham prediction using both trained models.

Dependencies
pandas
scikit-learn
Usage
Ensure you have Python installed.
Install the required dependencies using pip install -r requirements.txt.
Run the script using python spam_detection.py.
