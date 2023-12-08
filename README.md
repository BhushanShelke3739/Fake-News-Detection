
# Fake News Detection Web App

This is a simple web application for fake news detection using a machine learning model. It uses Flask for the web framework and scikit-learn for machine learning.

## Table of Contents

- [Fake News Detection Model](#fake-news-detection-model)
- [Dataset](#dataset)
- [Usage](#usage)
- [Dependencies](#dependencies)

## Fake News Detection Model
- The fake news detection model is built using the TF-IDF (Term Frequency-Inverse Document Frequency) vectorizer and a Passive Aggressive Classifier. 
- The TF-IDF vectorizer converts the text data into numerical features, and the Passive Aggressive Classifier is trained to classify news articles as either real or fake.

## Dataset
- The model is trained on a dataset of news articles that are labeled as real or fake. 
- The dataset used in this project is stored in the news.csv file. 
- It is recommended to update the dataset regularly to ensure the model's accuracy.
  
## Usage

1. Run the Flask app:

   ```bash
   python app.py


2. Open your web browser and go to [http://127.0.0.1:5000/](http://127.0.0.1:5000/).

3. Enter a news article in the provided input box and click the "Predict" button.

4. The app will display whether the news is predicted to be fake or not.

## Dependencies

- Flask
- scikit-learn
- pandas

Install the dependencies using the following:

```bash
pip install flask scikit-learn pandas

