# MACHINE-LEARING

COMPANY: CODTECH IT SOLUTIONS

NAME: AISHWARYA VEERANAGOUDA GIRIYAL

INTERN ID: CT04WU10

DOMAIN: PYTHON PROGRAMMING

DURATION: 4 WEEKS

MENTOR: NEELA SANTHOSH KUMAR

*DESCRIPTION*

## Project Explanation (500 Words)

The Spam Detection project is a supervised machine learning solution that aims to classify SMS messages as either "spam" or "ham" (not spam). This kind of text classification system is commonly used in email filters, messaging apps, and other communication tools to protect users from unwanted or potentially harmful content.

### Problem Statement

With the rise in communication through digital messaging, spam messages have become a significant nuisance. Many of these messages may contain advertisements, scams, or malicious links. The challenge is to build an intelligent system that can automatically detect and filter these messages, allowing only legitimate messages to reach the user. This project addresses that challenge using a machine learning-based classification approach.

### Dataset

The dataset used in this project is a labeled SMS dataset consisting of two columns: one for the label (`ham` or `spam`) and one for the actual message content. It contains over 5,000 examples, making it suitable for training and testing a basic spam classifier. Each message is categorized based on whether it is a genuine message or spam.

### Methodology

The workflow of the project follows a standard machine learning pipeline:

1. **Data Preprocessing**: The dataset is first cleaned by selecting only the relevant columns. No advanced preprocessing like stop word removal or stemming is applied here, as the model is designed to work with simple vectorized input.

2. **Text Vectorization**: The message data is converted into numerical form using `CountVectorizer`. This method converts each message into a vector of token counts, which the machine learning model can interpret.

3. **Model Loading**: Instead of training the model during each run, a pre-trained `Multinomial Naive Bayes` model is loaded using `joblib`. This ensures the project is efficient and easy to deploy.

4. **Prediction**: The model makes predictions on the input data, identifying whether each message is spam or ham.

5. **Evaluation**: The results are evaluated using accuracy score, confusion matrix, and a full classification report (precision, recall, F1-score). This gives a clear picture of how well the model performs.

6. **Output Generation**: All relevant outputs—including the predicted labels, metrics, and evaluations—are exported to a single Excel file using `pandas` and `openpyxl`. This file includes four sheets: Predictions, Confusion Matrix, Classification Report, and Accuracy.

### Results

The model achieves over 97% accuracy on the dataset, with strong performance across precision and recall metrics. The confusion matrix shows that very few messages are misclassified, indicating that the model generalizes well on unseen data.

### Deliverables

- A clean Jupyter Notebook (`.ipynb`) that demonstrates the entire process
- A trained model and vectorizer saved as `.joblib` files
- A full Excel report with predictions and evaluation metrics
- A structured GitHub repository with a README and documentation

This project demonstrates a strong foundational application of natural language processing and machine learning for real-world problems, making it an ideal addition to any data science portfolio.

*OUTPUT*

[spam_classification_output.xlsx](https://github.com/user-attachments/files/19906603/spam_classification_output.xlsx)

