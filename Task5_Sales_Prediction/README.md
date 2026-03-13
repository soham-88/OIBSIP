📈 Sales Prediction using Python
📌 Project Overview

Sales prediction is one of the most important applications of data science in business. Companies need to estimate future sales to make better decisions related to advertising budgets, marketing strategies, and revenue planning.

In this project, I built a Machine Learning regression model to predict product sales based on the amount spent on advertising through TV, Radio, and Newspaper.

This project demonstrates how machine learning can help businesses understand the relationship between advertisement spending and sales performance.

🎯 Objective

The main objectives of this project are:

To analyze how advertising budgets affect product sales

To understand relationships between TV, Radio, Newspaper, and Sales

To preprocess and clean the dataset

To build a regression model for sales prediction

To evaluate model performance using regression metrics

To predict sales for custom advertising values

📂 Dataset Information

The dataset contains the following columns:

TV – Advertising budget spent on TV

Radio – Advertising budget spent on Radio

Newspaper – Advertising budget spent on Newspaper

Sales – Sales of the product

An additional column Unnamed: 0 was present in the dataset and was removed during preprocessing because it was only an index column.

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

The dataset was loaded using Pandas and the first few rows were inspected.

3️⃣ Data Cleaning

The unnecessary Unnamed: 0 column was removed from the dataset.

4️⃣ Exploratory Data Analysis

Several visualizations were created to understand the relationship between advertising budgets and sales:

Correlation heatmap

Pairplot

TV vs Sales scatter plot

Radio vs Sales scatter plot

Newspaper vs Sales scatter plot

5️⃣ Feature Selection

The target variable was Sales, and the remaining columns were used as input features.

6️⃣ Train-Test Split

The dataset was split into:

80% training data

20% testing data

7️⃣ Model Training

A Linear Regression model was trained using the training dataset.

8️⃣ Model Evaluation

The model was evaluated using:

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

Root Mean Squared Error (RMSE)

R² Score

9️⃣ Prediction

The trained model was used to predict sales on test data and also on a custom sample input.

📈 Visualizations Included

This project includes the following visualizations:

Correlation Heatmap

Pairplot

TV vs Sales Scatter Plot

Radio vs Sales Scatter Plot

Newspaper vs Sales Scatter Plot

Actual vs Predicted Sales Plot

Residual Distribution Plot

📊 Model Performance

The Linear Regression model performed well in predicting sales and showed the relationship between advertisement spending and expected sales.

🧠 Conclusion

This project demonstrates how machine learning can be used to predict product sales based on advertising budgets. By using Linear Regression, the model was able to learn the relationship between ad spending and sales and make useful predictions.

This project also helped in understanding the workflow of a regression problem, including preprocessing, visualization, model training, evaluation, and prediction.

👨‍💻 Author

Soham Gopal Pawar
Data Science Intern
Oasis Infobyte Internship Program

