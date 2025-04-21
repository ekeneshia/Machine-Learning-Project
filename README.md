# Natural Language Processing with Disaster Tweets

## Table of Contents 
1. Project Description
2. Resources (Software and Tools)
3. Installation and Experiment run

## Project Description
Course Title: Machine Learning (CSC 4850/6850)

Group Members:
Fiyinfoluwa Dideoluwa, 
Ekene Okeke, and 
Josh Daisy 

Problem Statement:
During disasters such as earthquakes, floods, and wildfires, social media platforms like Twitter become relevant sources for gathering up to date information. However, the wide volume of tweets makes it difficult to manually filter relevant posts that provide vital updates on disasters from posts that are mere noise. This project focuses on developing an automated system to classify and extract critical disaster-related tweets, enabling faster and more effective emergency response. 

Goal and Motivation:
The goal of this project is to leverage Natural Language Processing (NLP) techniques to develop an automated system that effectively classifies and extracts disaster-related tweets to support emergency response efforts. The system will train and evaluate the performance of three deep learning models: Bidirectional Long Short-Term Memory (BiLSTM), Convolutional Neural Network (CNN), and Recurrent Neural Network (RNN). 

Project Assumptions:
- The dataset used for training is representative of real-world disaster-related tweets.
- The dataset used for training is representative of real-world disaster-related tweets. 
LSTM, CNN, and RNN are well-suited for text classification tasks, especially in identifying relevant disaster-related content.

Three labeled datasets were gotten from Kaggle:
1. [Dataset1](#https://www.kaggle.com/c/nlp-getting-started/data) 

## Resources (Software and Tools)
The project utilizes the following tools:
- **Python**: Main programming language for development 
- **TensorFlow/Keras**: Frameworks for building and training CNN, BiLSTM, and RNN models
- **Scikit-learn**: Used for model evaluation with metrics like accuracy, precision, recall, and F1-score.
- **Pandas & NumPy**: For data preprocessing and manipulation. 
- **Matplotlib/Seaborn:**: Visualization tools for exploratory data analysis and performance metrics. 


## Installation and Experiment run
1. Download the Code
Download the project code and save it to a convenient location on your computer.
Navigate to the Project Directory
Open a terminal or command prompt and change the directory to the project folder. 

2. Run Data Preprocessing
Before training any models, run the data preprocessing notebook to prepare the raw data:
- Open Data_Preprocessing.ipynb using Jupyter Notebook or any supported environment.
- Run all cells to complete the data preprocessing steps.

3. Run Individual Models
After preprocessing is complete, you can run each model notebook individually to train and evaluate the models.