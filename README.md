# 🔐 NLP Password Strength Classifier
This project uses Natural Language Processing (NLP) and machine learning techniques to classify the strength of passwords as Weak, Medium, or Strong based on their features. This solution can help users and organizations promote stronger password practices and enhance security.

### 🧠 Project Objective
To build a predictive model that can:

Analyze password text.

Extract relevant features using NLP.

Predict the password strength category (0 = Weak, 1 = Medium, 2 = Strong).

### 🔍 Dataset Overview
The dataset includes:

password: The password string.

strength: A numerical label representing password strength.

### ⚙️ Technologies Used
Python 🐍

pandas, NumPy – Data handling

scikit-learn – Machine Learning algorithms

NLTK – Tokenization and text preprocessing

TfidfVectorizer – Feature extraction

RandomForestClassifier, LogisticRegression – Classification models

Matplotlib, Seaborn – Visualization

### 📊 Model Development Steps
Data Cleaning & Preprocessing

Remove null values.

Visualize class distribution.

Analyze password characteristics.

Feature Engineering

Tokenization

TF-IDF vectorization

Model Training

Multiple classifiers were tested (e.g., Logistic Regression, Random Forest).

Accuracy and confusion matrix used to evaluate performance.

Model Evaluation

Evaluation on train-test split data.

Accuracy score and confusion matrix.

### ✅ Results
Achieved decent classification accuracy on distinguishing password strength categories.

Random Forest showed high performance on both training and testing sets.

### 📌 Future Enhancements
Use deep learning models like RNN or LSTM.

Include more complex password features (e.g., entropy, dictionary words).

Build a web app for real-time password strength checking.

👤 Author: Parth Sharma 
📧 Email: Parthsharma2300@gmail.com
🔗 LinkedIn: https://www.linkedin.com/in/parth-sharma-8288a7283
⭐ If you found this helpful, consider giving it a star!
