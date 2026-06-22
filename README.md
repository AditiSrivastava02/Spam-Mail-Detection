# Spam Mail Detection

A machine learning project for classifying email messages as **Spam** or **Ham (Not Spam)** using Natural Language Processing (NLP) techniques and supervised learning algorithms.

## Overview

Spam emails are unwanted messages that often contain advertisements, phishing attempts, or malicious content. This project builds a classification model that automatically detects spam messages and helps improve email filtering.

## Objectives

- Classify emails as Spam or Ham
- Perform text preprocessing and feature extraction
- Train and evaluate machine learning models
- Improve email security and user experience through automated filtering

## Dataset

The dataset contains labeled email or message records with:

- Message text
- Spam/Ham labels

Target Variable:

- Spam (1)
- Ham (0)

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- NLTK
- Matplotlib
- Seaborn

## Methodology

### 1. Data Preprocessing
- Remove unnecessary characters
- Convert text to lowercase
- Tokenization
- Stopword removal
- Text cleaning

### 2. Feature Extraction
- Bag of Words (BoW)
- TF-IDF Vectorization

### 3. Model Training
Typical models used for spam detection include:
- Naive Bayes
- Logistic Regression
- Support Vector Machine (SVM)
- Random Forest

### 4. Model Evaluation
Performance is evaluated using:
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

## Project Structure

```text
Spam-Mail-Detection/
├── Spam_Mail_Detection.ipynb
├── README.md
├── requirements.txt
└── outputs/
```

## How to Run

1. Clone the repository

```bash
git clone https://github.com/AditiSrivastava02/Spam-Mail-Detection.git
```

2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Launch Jupyter Notebook

```bash
jupyter notebook
```

4. Open the notebook and run all cells.

## Applications

- Email filtering systems
- Enterprise security solutions
- Phishing detection support
- Automated message classification

## Future Improvements

- Deep Learning models (LSTM, GRU, Transformers)
- Real-time spam detection API
- Web application deployment
- Multilingual spam classification

## Author

Aditi Srivastava
M.Tech Data Science & Analytics
