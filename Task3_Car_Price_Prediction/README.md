🚗 Car Price Prediction with Machine Learning
📌 Project Overview

Car price prediction is an important real-world machine learning application because the price of a car depends on several factors such as brand value, present showroom price, fuel type, kilometers driven, transmission type, and ownership history.

In this project, I built a Machine Learning regression model to predict the selling price of cars based on different car features. This project demonstrates how machine learning can be used to estimate prices using historical data.

🎯 Objective

The main objectives of this project are:

To analyze the factors affecting car prices

To preprocess and clean the dataset

To visualize the relationships between features

To train a regression model for car price prediction

To evaluate the model performance using regression metrics

To predict the selling price of a car based on input features

📂 Dataset Information

The dataset contains information about used cars with the following columns:

Car_Name – Name of the car

Year – Year in which the car was purchased

Selling_Price – Selling price of the car in lakhs

Present_Price – Current ex-showroom price of the car

Driven_kms – Total kilometers driven

Fuel_Type – Type of fuel used by the car

Selling_type – Dealer or Individual

Transmission – Manual or Automatic

Owner – Number of previous owners

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

Required libraries such as Pandas, NumPy, Matplotlib, Seaborn, and Scikit-learn were imported for data analysis, visualization, and machine learning.

2️⃣ Loading the Dataset

The dataset was loaded using Pandas and the first few rows were inspected to understand the dataset structure.

3️⃣ Data Preprocessing

The following preprocessing steps were performed:

Checked dataset information

Checked for missing values

Created a new feature called Car_Age from the Year column

Dropped unnecessary columns such as Year and Car_Name

Converted categorical variables into numeric format using one-hot encoding

4️⃣ Exploratory Data Analysis

Several visualizations were created to understand data patterns and feature relationships, including:

Correlation heatmap

Pairplot

Selling price distribution

Fuel type vs selling price

Transmission vs selling price

5️⃣ Feature Selection

The target variable was Selling_Price, while the remaining columns were used as input features.

6️⃣ Train-Test Split

The dataset was split into:

80% training data

20% testing data

7️⃣ Model Training

A Random Forest Regressor was used to train the car price prediction model.

8️⃣ Model Evaluation

The model was evaluated using:

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

Root Mean Squared Error (RMSE)

R2 Score

9️⃣ Custom Prediction

The trained model was also used to predict the selling price of a custom car sample.

📈 Visualizations Included

This project includes the following visualizations:

Correlation Heatmap

Pairplot

Selling Price Distribution

Fuel Type vs Selling Price

Transmission vs Selling Price

Actual Price vs Predicted Price

Feature Importance Graph

📊 Model Evaluation

The regression model performance was evaluated using standard regression metrics:

MAE measures the average prediction error

MSE measures squared error

RMSE gives the root of MSE

R2 Score shows how well the model explains the data

The model performed well in predicting used car prices.

🧠 Conclusion

This project demonstrates how machine learning can be applied to estimate the selling price of used cars based on important features. By using the Random Forest Regressor, the model was able to learn patterns from the dataset and make useful price predictions.

This project also helped in understanding the complete workflow of a regression-based machine learning project, including preprocessing, visualization, training, evaluation, and prediction.

👨‍💻 Author

Soham Gopal Pawar
Data Science Intern
Oasis Infobyte Internship Program
