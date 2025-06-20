# SENTIMENT-ANALYSIS-USING-NLP

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: DONTHIREDDY MAHIMA REDDY

*INTERN ID*:CT08DF57

*DOMAIN*: MACHINE LEARNING

*DURATION*: 8 WEEKS

*MENTOR*: NEELA SANTHOSH

# TASK-2

# DESCRIPTION :

# IMDb Movie Review Sentiment Analysis

This project performs **Sentiment Analysis** on IMDb movie reviews using **Natural Language Processing (NLP)** techniques. It classifies reviews as **positive** or **negative** by applying **TF-IDF vectorization** and a **Logistic Regression** model.

# Dataset

- **Source**: `IMDB Dataset.csv`
- **Size**: 50,000 movie reviews
- **Columns**:
  - `review`: Raw text of the movie review
  - `sentiment`: Sentiment label — `positive` or `negative`

# Objective

To build a machine learning model that can predict whether a movie review is **positive** or **negative** using NLP techniques.

# Technologies & Libraries

- **Python**
- **Pandas**, **NumPy**
- **Scikit-learn**
- **Seaborn**, **Matplotlib**
- **Regular Expressions**

# Workflow

# 1.Text Preprocessing
- Converted all text to **lowercase**
- Removed **punctuation, digits, and extra whitespace**
- Mapped sentiment labels to **binary values** (`positive` → 1, `negative` → 0)

# 2.Vectorization
- Used **TF-IDF Vectorizer** to convert text into numerical features
- Limited vocabulary to **top 5000 most relevant words**

# 3.Modeling
- Applied **Logistic Regression** for binary classification
- Split data: **80% for training**, **20% for testing**

# 4.Evaluation
- Achieved **accuracy of 89.3%**
- Displayed a **classification report** (precision, recall, F1-score)
- Visualized results using a **confusion matrix**

# Results

- **Model Accuracy**: `0.893`
- Strong performance in distinguishing between positive and negative sentiments

# Future Enhancements

- Experiment with **deep learning models** like LSTM or BERT
- Implement **hyperparameter tuning** for better performance
- Deploy as a **web app** using Streamlit or Flask

# Contact

For questions or feedback, feel free to reach out at **[Your Email]** or connect on **[LinkedIn]**.

# OUTPUT :

Precision, Recall, F1 Score:

Confusion Matrix:

![Image](https://github.com/user-attachments/assets/e5fff568-949e-4ac5-aeaf-bfa5ae51cd23)





