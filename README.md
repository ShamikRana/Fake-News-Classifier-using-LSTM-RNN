# Fake News Classifier using LSTM RNN
Fake news is a form of news consisting of deliberate disinformation or hoaxes spread via traditional news media or online social media. In this project, I have used LSTM based classifier to detect fake news from news headlines.

# Methods Used
- Data Cleaning
- Data Wrangling
- Data Preprocessing
- Word Embedding
- Deep Learning (Long Short Term Memory Neural Network)

# Technologies Used
- Pyhton
- Jupyter
- Numpy, Pandas, NLTK
- Scikit Learn, Tensorflow

# Project Description
- Project began with fetching of data from [Kaggle dataset](https://www.kaggle.com/datasets/shamikrana/news-articles)
- Data is cleaned by removing null values and useless columns
- Data is preprocessed by using regex, lemmatization and stopwords
- Embedding layer is added into LSTM model with a vocabulary size of 10,000 words and 400 vector features
- Dataset is divided in 80:20 ratio as test and train dataset
- Model is trained with LSTM neural network

# Findings
The architecture and parameter used in this neural network are capable of producing accuracy of 82.49% on Test Data

# How to Use
- Fork this repository to have your own copy
- Clone your copy on your local system
- Install necessary packages
