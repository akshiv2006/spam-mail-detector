# Spam Mail Detector

## Project Overview

This project was developed as part of my Artificial Intelligence and Machine Learning Virtual Internship.

The objective of this project is to build a machine learning model that classifies SMS messages into two categories:

- Ham (Not Spam)
- Spam

The project uses Natural Language Processing (NLP) techniques and the Multinomial Naive Bayes algorithm to classify messages accurately.

---

## Dataset

The project uses the **SMS Spam Collection Dataset**.

- Total Messages: 5,572
- Classes:
  - Ham
  - Spam

Each message is labeled as either spam or ham.

---

## Technologies Used

- Python
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook
- Visual Studio Code

---

## Project Workflow

1. Import required libraries
2. Load the SMS Spam Collection dataset
3. Explore the dataset
4. Perform label encoding
5. Split the dataset into training and testing sets
6. Convert text into numerical features using TF-IDF Vectorization
7. Train the Multinomial Naive Bayes classifier
8. Make predictions on the test data
9. Evaluate the model using:
   - Accuracy
   - Precision
   - Recall
   - F1-Score
   - Confusion Matrix
10. Test the model with custom SMS messages

---

## Machine Learning Model

Algorithm Used:

- Multinomial Naive Bayes

Feature Extraction:

- TF-IDF Vectorizer

Train-Test Split:

- 80% Training Data
- 20% Testing Data

---

## Model Performance

The model achieved high accuracy in detecting spam messages.

Evaluation metrics include:

- Accuracy Score
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## Project Structure

```
spam_mail_detector/
│
├── spam_mail_detector.ipynb
├── SMSSpamCollection
├── README.md
└── requirements.txt
```

---

## How to Run the Project

1. Clone this repository.

2. Install the required libraries.

```bash
pip install -r requirements.txt
```

3. Open the notebook.

```bash
jupyter notebook spam_mail_detector.ipynb
```

4. Run all cells.

---

## Requirements

- pandas
- matplotlib
- scikit-learn
- jupyter

---

## Future Improvements

- Add email spam detection.
- Build a web application using Flask or Streamlit.
- Deploy the model online.
- Improve preprocessing with stemming and lemmatization.

---

## Conclusion

This project demonstrates the complete Natural Language Processing (NLP) workflow for spam message classification.

The model converts SMS messages into numerical features using TF-IDF Vectorization and classifies them using the Multinomial Naive Bayes algorithm.

The trained model successfully identifies whether a message is spam or ham and achieves high classification performance.

---

## Author

**Akshiv Varsha**