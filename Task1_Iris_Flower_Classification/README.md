🌸 Iris Flower Classification using Machine Learning
📌 Project Overview

The Iris Flower Classification project is a classic Machine Learning classification problem used to demonstrate how data science techniques can be applied to predict categories based on input features.

In this project, a machine learning model was built to classify iris flowers into three species using measurements of the flower's petals and sepals.

The three species of iris flowers are:

Iris-setosa

Iris-versicolor

Iris-virginica

Using the dataset features such as sepal length, sepal width, petal length, and petal width, the model learns patterns and predicts the species of the flower.

🎯 Objective

The main objectives of this project are:

To understand the structure of the Iris dataset

To perform data preprocessing and exploratory data analysis

To visualize relationships between features

To train a Machine Learning classification model

To evaluate the model performance using different metrics

To predict the species of iris flowers based on new input data

📂 Dataset Information

The dataset used in this project is the Iris Dataset, which is one of the most well-known datasets in machine learning.

The dataset contains 150 samples of iris flowers with the following features:

Feature	Description
SepalLengthCm	Length of the sepal in centimeters
SepalWidthCm	Width of the sepal in centimeters
PetalLengthCm	Length of the petal in centimeters
PetalWidthCm	Width of the petal in centimeters
Species	Target variable representing flower species

Each flower belongs to one of the three species:

Iris-setosa

Iris-versicolor

Iris-virginica

🛠 Technologies Used

The following tools and libraries were used in this project:

Python

Pandas – Data manipulation and analysis

NumPy – Numerical computations

Matplotlib – Data visualization

Seaborn – Advanced statistical visualization

Scikit-learn – Machine learning model training

Jupyter Notebook – Development environment

⚙️ Project Workflow

The project was completed through the following steps:

1️⃣ Importing Required Libraries

The first step was importing essential Python libraries such as Pandas, NumPy, Matplotlib, Seaborn, and Scikit-learn.

These libraries help in:

data manipulation

data visualization

machine learning model training

2️⃣ Loading the Dataset

The Iris dataset was loaded using the Pandas library.

After loading the dataset, the first few rows were displayed to understand the structure of the data.

3️⃣ Data Preprocessing

Before training the model, several preprocessing steps were performed:

Checked dataset information

Checked for missing values

Removed unnecessary columns such as Id

Verified that the dataset contains valid numerical values

These steps ensure the dataset is clean and suitable for machine learning.

4️⃣ Exploratory Data Analysis (EDA)

Exploratory Data Analysis was performed to understand relationships between the dataset features.

Pairplot Visualization

A pairplot was used to visualize relationships between different features and observe how different species are distributed.

This visualization shows that Iris-setosa is easily separable from the other species.

Correlation Heatmap

A heatmap was created to visualize correlations between numerical features such as:

sepal length

sepal width

petal length

petal width

This helps identify relationships between variables.

🤖 Machine Learning Model
Splitting the Dataset

The dataset was divided into training and testing sets using the train_test_split method.

80% data → Training

20% data → Testing

This ensures the model is tested on unseen data.

Model Selection

The Random Forest Classifier algorithm was used for this classification task.

Random Forest is an ensemble learning algorithm that combines multiple decision trees to improve prediction accuracy.

Model Training

The model was trained using the training dataset so it could learn patterns between input features and flower species.

Model Prediction

After training the model, predictions were made using the testing dataset to determine how accurately the model can classify iris flowers.

📊 Model Evaluation

The model performance was evaluated using several metrics.

Accuracy Score

Accuracy measures how many predictions were correct compared to the total number of predictions.

The model achieved high accuracy in classifying iris species.

Confusion Matrix

A confusion matrix was generated to visualize the performance of the classification model.

It shows:

correct predictions

incorrect predictions

Classification Report

A classification report was generated to evaluate:

Precision

Recall

F1-score

Support

These metrics provide a deeper understanding of the model's performance.

🔍 Custom Prediction

The trained model was also tested with a custom sample input containing flower measurements.

Example input:

Sepal Length = 5.1
Sepal Width = 3.5
Petal Length = 1.4
Petal Width = 0.2

The model predicted the species as:

Iris-setosa

This confirms that the model successfully learned patterns from the dataset.

📊 Visualizations Included

The project includes several visualizations:

Pairplot of dataset features

Correlation heatmap

Confusion matrix

These visualizations help understand the dataset and evaluate model performance.

📷 Project Visualizations

Screenshots of the following outputs are included in the repository:

Dataset preview

Pairplot visualization

Heatmap

Model accuracy output

Confusion matrix

Classification report

🎥 Project Demonstration

A short video demonstration was recorded explaining:

Dataset overview

Data preprocessing

Exploratory data analysis

Model training

Prediction results

The video was shared on LinkedIn as part of the Oasis Infobyte internship task submission.

🧠 Conclusion

This project demonstrates how Machine Learning can be used to classify data based on patterns in features.

Using the Random Forest Classifier, the model successfully learned relationships between flower measurements and species, achieving high prediction accuracy.

The Iris dataset is an excellent example for understanding the complete machine learning workflow, including data preprocessing, visualization, model training, and evaluation.

👨‍💻 Author

Soham Gopal Pawar
Data Science Intern
Oasis Infobyte Internship Program
