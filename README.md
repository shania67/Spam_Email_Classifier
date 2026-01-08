# Email Spam Classifier Using Naive Bayes

This project implements an Email Spam Classification system using
Machine Learning and the Multinomial Naive Bayes algorithm.  
The model is developed and executed using **Google Colab**.

## Project Overview
Spam emails are unsolicited messages that may contain advertisements,
fraudulent offers, or malicious content. This project uses Natural
Language Processing (NLP) techniques to automatically classify emails
as spam or non-spam (ham) based on their textual content.

## Features
- Text preprocessing (lowercasing, punctuation removal, stopword removal)
- TF-IDF feature extraction
- Multinomial Naive Bayes classifier
- High accuracy spam detection
- Implemented using Google Colab

## Technologies Used
- Python
- Google Colab
- Pandas
- NumPy
- Scikit-learn
- NLTK

## Dataset
**spam_or_not_spam.csv**
- `email` → Email text content
- `label` → 0 = Not Spam, 1 = Spam
- Total records: 3000 emails

## How to Run the Project
1. Open Google Colab  
2. Upload the `Email_Spam_Classifier.ipynb` notebook  
3. Upload the `spam_or_not_spam.csv` dataset  
4. Run all cells sequentially

No local installation is required.

## Results
The Naive Bayes classifier achieves high accuracy in distinguishing
between spam and non-spam emails, demonstrating the effectiveness
of machine learning for text classification tasks.

## Future Enhancements
- Use deep learning models such as LSTM or BERT
- Analyze email headers
- Deploy as a web application using Flask
