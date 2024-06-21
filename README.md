# Sonar Rock or Mine Prediction using Logistic Regression Model

## Overview
This project involves building a logistic regression model to classify sonar signals as either rocks or mines. The dataset used contains sonar signals bounced off different objects, and the goal is to determine whether the object is a rock or a mine based on the characteristics of the returned signals.

## Dataset
The dataset used for this project is the "Sonar, Mines vs. Rocks" dataset, which is available from the UCI Machine Learning Repository. The dataset contains 208 instances and 60 attributes, each representing the strength of the sonar signal at a particular angle. The last column is the target variable indicating whether the object is a mine (M) or a rock (R).

## Prerequisites
To run this project, you need to have the following software installed:
- Python 3.x
- Jupyter Notebook (optional, but recommended for an interactive environment)
- Required Python libraries: `numpy`, `pandas`, `scikit-learn`, `matplotlib`

You can install the required Python libraries using the following command:
```bash
pip install numpy pandas scikit-learn matplotlib
```

## Project Structure
The project directory contains the following files:
- `sonar_rock_mine_logistic_regression.ipynb`: Jupyter Notebook containing the entire workflow for the logistic regression model.
- `sonar_all_data.csv`: The dataset file containing the sonar signals data.
- `README.md`: This readme file providing an overview of the project.

## Steps to Run the Project

1. **Clone the Repository**: Clone the project repository to your local machine.
    ```bash
    git clone https://github.com/Ravij-p/SonarRockOrMineLogisticRegression.git
    cd SonarRockOrMineLogisticRegression
    ```

2. **Load the Dataset**: Load the dataset using pandas.

3. **Data Preprocessing**:
    - Split the data into features (`X`) and target (`y`).
    - Convert target labels from categorical ('R', 'M') to binary (0, 1).
    - Split the dataset into training and testing sets using `train_test_split` from scikit-learn.

4. **Train the Model**:
    - Train a logistic regression model using `LogisticRegression` from scikit-learn.

5. **Model Evaluation**:
    - Evaluate the model on the testing set.
    - Calculate accuracy.

## Conclusion
This project demonstrates how to build and evaluate a logistic regression model for classifying sonar signals as rocks or mines. The provided Jupyter Notebook walks through the entire process, from loading the data to training the model and evaluating its performance.

Feel free to explore and modify the code to improve the model or try different machine learning algorithms.
