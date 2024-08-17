Phishing Classifier

Overview

The Phishing Classifier is a machine learning-based web application that detects phishing websites based on various features extracted from URLs. It takes a CSV file as input, processes it through a trained model, and returns a CSV file with a prediction for each URL. The prediction is binary:

0 indicates a legitimate website.
1 indicates a phishing website.

Features

Input: Accepts a CSV file containing URLs or relevant features.
Output: Generates a CSV file with predictions for each entry.
Model: Utilizes a machine learning model trained on phishing data.
Logging and Validation: Includes mechanisms for data validation and logging to ensure accurate predictions.

How It Works

Upload CSV: The user uploads a CSV file containing the URLs or specific features of URLs that need to be classified.
Validation: The system validates the input data to ensure it meets the required schema (e.g., correct number of columns).
Prediction: The data is processed through a machine learning pipeline that classifies each entry as either phishing or legitimate.
Download Results: The user can download a CSV file containing the original data with an additional column for the phishing prediction.




'''pip install -e .''' to run setup.py
