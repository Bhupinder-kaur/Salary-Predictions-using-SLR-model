# Salary-Predictions-using-SLR-model
Simple Linear Regression on Salary Data
This project demonstrates a basic implementation of Simple Linear Regression using Python and scikit-learn. The goal is to predict salaries based on years of experience, using a simple linear regression model.

Key Features:
Data Handling: The dataset is loaded and split into independent (Years of Experience) and dependent (Salary) variables.
Train-Test Split: The dataset is divided into training and testing sets using an 80-20 split.
Model Training: A linear regression model is trained using the training data.
Prediction: The model is tested on the test set, and predictions are compared with actual results.
Visualization: Graphs are plotted to visualize the relationship between years of experience and salary for both training and test data.
Model Evaluation: The performance of the model is evaluated using:
R-squared (Training and Testing)
Mean Squared Error (MSE)
Salary Prediction: Predictions are made for 12 and 20 years of experience.
Pickle the Model: The trained model is saved to a .pkl file for future use.
Visualizations:
Training Set Visualization: Displays the relationship between years of experience and salary for the training data.
Test Set Visualization: Displays how the trained model performs on the test data.
Usage:
To use this project:

Install the required dependencies (listed below).
Update the path to the dataset in the script if necessary.
Run the script to train the model and make predictions.
Visualizations and performance metrics are printed to the console.
Dependencies:
Python 3.x
pandas
numpy
matplotlib
scikit-learn
pickle
How to Run:
Clone the repository.
Ensure all dependencies are installed.
Modify the dataset path if needed.
Run the script to see results and visualizations.
Example Output:
The script outputs the comparison between actual and predicted salaries, visualizes the regression line for training and test data, and predicts salaries for 12 and 20 years of experience. The trained model is also saved as linear_regression_model.pkl.
