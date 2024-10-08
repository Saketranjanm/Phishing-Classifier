Phishing Classifier

Overview

The Phishing Classifier is a machine learning-based web application that detects phishing websites based on various features extracted from URLs. It takes a CSV file as input, processes it through a trained model, and returns a CSV file with a prediction for each URL. 

Features           

Input: Accepts a CSV file containing URLs or relevant features.              
Output: Generates a CSV file with predictions for each entry.                           
Model: Utilizes a machine learning model trained on phishing data.                             
Logging and Validation: Includes mechanisms for data validation and logging to ensure accurate predictions. 

How It Works

Upload CSV: The user uploads a CSV file containing the URLs or specific features of URLs that need to be classified.           
Validation: The system validates the input data to ensure it meets the required schema .            
Prediction: The data is processed through a machine learning pipeline that classifies each entry as either phishing or legitimate.         
Download Results: The user can download a CSV file containing the original data with an additional column for the phishing prediction.


OUTPUTS:

prediction window:
![Screenshot (279)](https://github.com/user-attachments/assets/f1063736-fb41-4232-9c84-c53b0fbf74fd)

original file:
![Screenshot (281)](https://github.com/user-attachments/assets/f346d050-6e9d-4a83-8eda-ded915298f93)

file with prediction result in last column:
![Screenshot (280)](https://github.com/user-attachments/assets/fd461e45-8cb2-462d-bced-aaf73ab04328)



'''pip install -e .''' to run setup.py
