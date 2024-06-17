
# Project Title

Rock vs Mine Prediction




## Appendix


This project utilizes a Logistic Regression model to classify objects as either rocks or mines based on sonar signal data. The dataset contains samples of sonar signals bounced off various objects, and the goal is to predict the type of object (rock or mine).

Installation

To run this project, you'll need Python and the following libraries installed:

numpy
pandas
scikit-learn
You can install the required libraries using pip:

bash
Copy code
pip install numpy pandas scikit-learn
Dataset
The dataset used for this project is the Sonar dataset. Each sample consists of 60 features representing the energy of sonar signals bounced off objects at different angles. The target variable has two possible values: 'R' (rock) and 'M' (mine).

## Functionalities
Data Loading: Loads the dataset into a Pandas DataFrame.

Data Preprocessing: Separates features and target labels, and splits the dataset into training and testing sets.

Model Training: Trains a Logistic Regression model on the training data.

Model Evaluation: Evaluates the model's accuracy on both the training and testing data.

Prediction: Uses the trained model to make predictions on new data.
