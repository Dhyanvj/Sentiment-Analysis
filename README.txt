Sentiment Analysis using Naive Bayes Classifier

Overview
This Python script performs sentiment analysis on restaurant reviews using a Naive Bayes Classifier. The analysis includes data cleaning, visualization of word clouds, text representation, model training, evaluation, and predictions on unseen data.

Getting Started
Prerequisites
Python 3.x
Required Python libraries: numpy, pandas, nltk, tensorflow, keras, matplotlib, seaborn, wordcloud, scikit-learn

Usage
Data Preparation:
- Download the dataset from Kaggle (https://www.kaggle.com/datasets/d4rklucif3r/restaurant-reviews/data) and save it as Restaurant_Reviews.tsv.
- Ensure the dataset file is placed in the same directory as the script.
- Replace the file path of the Restaurant_Reviews.tsv in the variable known as Data.
- For making predictions i have given an example file of unssen reviews named Restaurant Reviews.csv.
- Before making predictions replace the path in the variable unseen_data with the file path of the Restaurant Reviews.csv given in my provided folder.

Results:
The script will display visualizations, model evaluation metrics, and predictions on unseen data.

File Descriptions
sentiment_analysis.py: The main Python script containing the sentiment analysis code.
Restaurant_Reviews.csv: The unseen reviews to make predictions on.
README.md: This documentation file.

Customization
Adjust hyperparameters and configurations in the script to suit specific requirements.
Experiment with different tokenization and preprocessing techniques.

Additional Information
The script uses a Naive Bayes Classifier implemented from scratch for sentiment analysis.
Visualization includes word clouds for positive and negative reviews.
Model evaluation metrics include accuracy, confusion matrix, precision, recall, specificity, and a classification report.

Author
Dhyan Nilesh Patel