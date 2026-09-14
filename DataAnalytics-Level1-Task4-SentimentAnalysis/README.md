# Sentiment Analysis

## Oasis Infobyte Internship

Name: Prince Kumar  
Track: Data Analytics  
Level: Level 1  
Task: Task 4 - Sentiment Analysis



## Project Overview
This project focuses on building a machine learning based sentiment
analysis system that classifies Twitter text into three sentiment
categories:
  - Positive
  - Negative
  - Neutral

The project was completed as part of the Oasis Infobyte Data Analytics
Internship.



## Objective
The main objective is to preprocess text data, convert textual data into
numerical features using TF-IDF, train machine learning classification
models, evaluate their performance, and analyze classification errors.



## Dataset
The project uses the **Twitter Sentiment Analysis (Entity-level)**
dataset containing Twitter posts with sentiment labels.

The original dataset contains four categories:
- Positive
- Negative
- Neutral
- Irrelevant

The Irrelevant class was removed because this project focuses on
Positive, Negative, and Neutral sentiment classification.

After preprocessing, the final dataset contained **60,239 records**.



## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- NLTK
- Matplotlib
- Seaborn
- WordCloud
- Google Colab




## Data Preprocessing
The following preprocessing steps were performed:

1. Converted text to lowercase
2. Removed URLs
3. Removed punctuation
4. Tokenized the text
5. Removed English stopwords
6. Removed non-alphabetic tokens
7. Removed empty cleaned text records




## TF-IDF Feature Extraction
TF-IDF (Term Frequency-Inverse Document Frequency) was used to convert
text data into numerical feature vectors.

A maximum of 5,000 TF-IDF features was used for machine learning
classification.




## Machine Learning Models
Two classification algorithms were trained:

 1. Multinomial Naive Bayes
    Accuracy: **72.97%**

 2. Logistic Regression
    Accuracy: **76.34%**



## Model Performance

| Model                   | Accuracy | Precision | Recall | F1-Score |
| Multinomial Naive Bayes | 72.97%   | 73.11%    | 72.97% | 72.60% |
| Logistic Regression     | 76.34%   | 76.27%    | 76.34% | 76.28% |


### Best Model
Logistic Regression :  performed better than Multinomial Naive Bayes
based on the overall evaluation metrics.



## Visualizations
The project includes:

- Sentiment distribution bar chart
- Naive Bayes confusion matrix
- Logistic Regression confusion matrix
- Model performance comparison
- Negative sentiment WordCloud
- Neutral sentiment WordCloud
- Positive sentiment WordCloud



## Error Analysis
Five misclassified examples were examined to understand why the model
made incorrect predictions.

Common reasons include:
- Ambiguous language
- Sarcasm and irony
- Short text
- Context dependency
- Similar vocabulary between sentiment classes



## Real-World Applications
Sentiment analysis can be used for:
- Social media monitoring
- Customer feedback analysis
- Product and service review analysis
- Brand reputation monitoring
- Customer support analysis
- Business decision-making



## Conclusion
The project demonstrates how Natural Language Processing and machine
learning can be used to automatically classify sentiment from Twitter
text.

Among the two tested models, Logistic Regression achieved the best
performance with an accuracy of **76.34%** and an F1-score of **76.28%**.

The project also demonstrates the importance of text preprocessing,
feature extraction, model evaluation, visualization, and error analysis
in a complete machine learning workflow.
