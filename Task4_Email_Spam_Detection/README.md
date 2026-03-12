📧 Email Spam Detection with Machine Learning
📌 Project Overview

Spam messages and emails are one of the most common problems in digital communication. They often contain advertisements, scams, fraudulent offers, or phishing content. Detecting spam automatically is an important machine learning application that helps improve digital security and user experience.

In this project, I built a Machine Learning model to classify messages as Spam or Ham (non-spam) using Python and Natural Language Processing techniques.

🎯 Objective

The main objectives of this project are:

To clean and preprocess text data

To analyze spam and ham message distribution

To convert text data into numerical format

To train a machine learning model for spam detection

To evaluate model performance

To classify custom messages as spam or non-spam

📂 Dataset Information

The dataset contains message text and labels:

v1 – label (ham or spam)

v2 – message content

Additional unnamed columns were removed during preprocessing because they were empty and unnecessary.

After cleaning:

label → spam/ham

message → actual message text

🛠 Technologies Used

The following tools and libraries were used:

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Jupyter Notebook

⚙️ Project Workflow
1️⃣ Importing Libraries

Required libraries such as Pandas, NumPy, Matplotlib, Seaborn, and Scikit-learn were imported.

2️⃣ Loading the Dataset

The dataset was loaded using Pandas with latin1 encoding.

3️⃣ Data Cleaning

The following preprocessing steps were performed:

Removed unnecessary unnamed columns

Renamed columns to meaningful names

Checked for null values

Removed duplicate rows

4️⃣ Exploratory Data Analysis

The following analyses were performed:

Count of spam and ham messages

Countplot for class distribution

Message length analysis

Histogram of message lengths

5️⃣ Label Encoding

The label column was converted into numeric format:

ham = 0

spam = 1

6️⃣ Text Vectorization

Text data was converted into numeric form using TF-IDF Vectorization.

7️⃣ Train-Test Split

The dataset was split into:

80% training data

20% testing data

8️⃣ Model Training

A Multinomial Naive Bayes classifier was trained on the vectorized text data.

9️⃣ Model Evaluation

The model was evaluated using:

Accuracy Score

Confusion Matrix

Classification Report

🔟 Custom Predictions

The trained model was used to classify custom sample messages as spam or ham.

📈 Visualizations Included

This project includes the following visualizations:

Spam vs Ham countplot

Message length distribution histogram

Confusion matrix heatmap

📊 Model Performance

The model achieved high accuracy in detecting spam messages and performed well on unseen test data.

🧠 Conclusion

This project demonstrates how machine learning and text processing techniques can be used to detect spam messages automatically. By using TF-IDF vectorization and the Multinomial Naive Bayes algorithm, the model was able to classify messages as spam or ham with high accuracy.

This project also helped in understanding the workflow of a Natural Language Processing classification problem, including text cleaning, vectorization, model training, evaluation, and prediction.

👨‍💻 Author

Soham Gopal Pawar
Data Science Intern
Oasis Infobyte Internship Program
