Twitter Sentiment Analysis
📌 Project Overview

This project analyzes sentiments from Twitter data using the Sentiment140 dataset. The dataset contains 1.6 million tweets labeled as positive, negative, or neutral. The goal is to preprocess tweets, extract features, and train a machine learning model to classify sentiment.

⚙️ Technologies & Tools Used

Python 3

Jupyter Notebook / Google Colab

Libraries:

pandas, NumPy → Data manipulation & analysis

re, NLTK (stopwords, stemming) → Text preprocessing

scikit-learn → Feature extraction (TF-IDF), model training (Logistic Regression), evaluation

Matplotlib / Seaborn → Data visualization (if used)

Kaggle API → Dataset import (Sentiment140)

📂 Dataset

Name: Sentiment140

Source: Sentiment140 Dataset on Kaggle

Description: Contains 1.6M tweets labeled as 0 = Negative, 2 = Neutral, 4 = Positive.

⚠️ Due to size limits, the full dataset is not included in this repository. You can download it directly from Kaggle.
A sample dataset is provided for quick testing.

🚀 Project Workflow

Data Collection

Fetched Sentiment140 dataset using Kaggle API.

Data Preprocessing

Removed special characters, numbers, and stopwords.

Tokenized and stemmed text.

Converted text to numerical vectors using TF-IDF.

Model Building

Split data into train and test sets.

Trained Logistic Regression classifier.

Evaluated using accuracy score.

Results

Achieved good accuracy in classifying tweets as positive/negative/neutral.

📊 Results & Insights

Logistic Regression works well for sentiment analysis with TF-IDF features.

Preprocessing (cleaning + stemming) significantly improves accuracy.

Future work: try advanced models like Naive Bayes, SVM, LSTMs, or BERT.

📌 Dataset link
https://www.kaggle.com/datasets/kazanova/sentiment140

👩‍💻 Author

Mihika Jain
