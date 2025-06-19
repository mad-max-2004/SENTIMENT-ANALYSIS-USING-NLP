# SENTIMENT-ANALYSIS-USING-NLP

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: DONTHIREDDY MAHIMA REDDY

*INTERN ID*:CT08DF57

*DOMAIN*: MACHINE LEARNING

*DURATION*: 8 WEEKS

*MENTOR*: NEELA SANTHOSH

*TASK-2*

*DESCRIPTION*:

This project performs sentiment analysis using Natural Language Processing (NLP) techniques. It classifies IMDb movie reviews as either positive or negative using TF-IDF vectorization and Logistic Regression.

->Dataset:
Source: IMDB Dataset.csv,
Size: 50,000 reviews

Columns:

review: Raw text review

sentiment: Label - either positive or negative

->Objective:
To build an NLP model that can predict the sentiment of a movie review using TF-IDF and Logistic Regression.

Technologies & Tools:
Python,
Pandas, NumPy ,
Seaborn, Matplotlib ,
Scikit-learn ,
Regular Expressions

->Workflow:

1. Text Preprocessing :
Converted all text to lowercase

Removed punctuation, digits, and extra whitespace

Mapped sentiment labels to binary values: positive → 1, negative → 0

2. Vectorization :
Applied TF-IDF Vectorizer to convert text into numerical feature vectors

Limited to top 5000 most relevant words

3. Modeling :
Used Logistic Regression as the classification algorithm

Trained on 80% of the dataset and tested on 20%

4. Evaluation :
Achieved an accuracy of ~89.3%

Displayed Classification Report (Precision, Recall, F1-Score)

Visualized Confusion Matrix

->Results 

Accuracy: 0.893

#OUTPUT :

Precision, Recall, F1 Score:

Confusion Matrix:

![Image](https://github.com/user-attachments/assets/e5fff568-949e-4ac5-aeaf-bfa5ae51cd23)





