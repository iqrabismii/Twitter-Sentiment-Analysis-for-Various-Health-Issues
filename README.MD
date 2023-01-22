# :incoming_envelope: Twitter Sentiment Analysis 

[![](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=darkgreen)](https://www.python.org)  [![](https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/stable/) 
[![](https://img.shields.io/badge/SciPy-654FF0?style=for-the-badge&logo=SciPy&logoColor=white)](https://www.scipy.org) 
[![](https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white)](https://numpy.org)
[![](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org)
[![](https://img.shields.io/badge/conda-342B029.svg?&style=for-the-badge&logo=anaconda&logoColor=white)](https://www.anaconda.com)
![Power Bi](https://img.shields.io/badge/power_bi-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)

## Problem Statement

To analyze people's reactions towards diseases such as heart diseases, arthritis, and Alzheimer's using natural language processing (NLP) techniques on tweets. The goal is to help doctors understand how to interact with their patients effectively by identifying common concerns and sentiments expressed by patients and their families on social media. 
The analysis will provide insights into the patient experience, which can help doctors improve their communication and care strategies.

## Natural Language Processing (NLP)
In this project, we utilized several __natural language processing (NLP)__ techniques to 
analyze people's reactions towards diseases such as heart disease, arthritis, and Alzheimer's. 
These techniques included __subjectivity__ and __polarity__ analysis using __TextBlob__, __lemmatization__ and __stemming__ 
to standardize the words in the tweets, and removing stop words to focus on the important keywords. Additionally, 
we also applied n-grams analysis to identify common phrases within the tweets.
These techniques were used to gain insights on how doctors can interact with patients more effectively.

## Data Preprocessing 
The tweets were cleaned by removing hyperlinks, extra special characters and converting emojis 
to text using the python emoji module. This was done to standardize the data and make it more consistent. 
Additionally, regular expressions were used to further clean the data and remove any remaining inconsistencies. 
This step helped to ensure that the data was ready for analysis and could be used to accurately identify patterns 
and trends in the tweets related to diseases such as heart diseases, arthritis and Alzheimer's. Overall, 
the data preprocessing step helped to improve the accuracy and reliability of the results obtained from the analysis.

## Exploratory Data Analysis (EDA)

In the exploratory data analysis (EDA) phase of this project, various techniques were used to understand the tweets related to diseases such as heart diseases, arthritis, and Alzheimer's. These techniques included:

* Word cloud: A word cloud is a visual representation of the most frequently used words in a dataset. In this project, word clouds were used to see the most common words used in tweets related to the diseases.

* Bar charts: Bar charts were used to see the distribution of tweets with hyperlinks, question marks, and other special characters. This helped in understanding the nature of tweets, whether they were informative or just questions.

* N-grams: N-grams are a set of co-occurring words within a given window. In this project, bigrams and trigrams were used to analyze the positive and negative words used in tweets.

* Sentiment Analysis: Sentiment analysis is the process of determining the emotional tone behind a series of words, used to identify and extract subjective information from source materials. In this project, NLTK library was used to perform sentiment analysis and classify the tweets into positive, neutral and negative sentiments.

By performing these EDA techniques, the team was able to gain a better understanding of the tweets related to the diseases and identify patterns and trends that could be useful in helping doctors interact with patients.

More details are provided in this [notebook.](https://github.com/iqrabismii/Twitter-Sentiment-Analysis-for-Various-Health-Issues/blob/main/CongestiveHeartFailure_Twitter_Feed_Analysis_08022022.ipynb)

## Data Visualisation and Insights

A dashboard was created using Power BI to display the sentiment analysis of tweets related to various diseases such as heart disease, arthritis and Alzheimer's. The dashboard includes a word cloud for each disease, showing the most frequently used words in tweets related to that disease. It also includes a pie chart displaying the distribution of positive, negative and neutral tweets for each disease. Additionally, the most frequent emoticons used in tweets related to each disease were extracted and included in the dashboard. Through this analysis, it was observed that people had a more serious attitude towards heart disease compared to Alzheimer's.
Link to Power BI dashboard is provided [here.](https://github.com/iqrabismii/Twitter-Sentiment-Analysis-for-Various-Health-Issues/blob/main/Tweet_Analysis_v6.pdf)



