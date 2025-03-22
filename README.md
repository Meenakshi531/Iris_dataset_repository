# Iris Flower Classification

This project predicts the species of Iris flowers using machine learning models. The dataset includes measurements of sepal length, sepal width, petal length, and petal width to classify three species: Iris-setosa, Iris-versicolor, and Iris-virginica.##

## Features:

- Sepal Length (cm)

- Sepal Width (cm)

- Petal Length (cm)

- Petal Width (cm)

Target: Species (setosa, versicolor, virginica)

## Data Preprocessing

Load Dataset: Imported dataset using sklearn.datasets.load_iris().

Convert to DataFrame: Converted dataset to Pandas DataFrame.

Split Data: Separated features (X) and target (y).

Train-Test Split: Split the data into 80% training and 20% testing using train_test_split().

## Model Selection

The following models were used:

Logistic Regression

Random Forest Classifier provided the best accuracy.

## Model Evaluation

Metrics used to evaluate the models:

1. Accuracy: Measures the proportion of correct predictions.

2. Confusion Matrix: Displays the actual vs. predicted values.

3. Classification Report: Shows precision, recall, and F1-score.


## Final Model: Logistic Regression

Accuracy: 97.5% on the test set

training accuracy: 100% average


## Results Visualization

Confusion Matrix: Displays the true vs. predicted classifications.

Feature Importance: Shows which features influence predictions the most.

## How to Run the Project

Clone the repository:

git clone <https://github.com/Meenakshi531/Iris_dataset_repository>
cd Iris_dataset_repository

Install dependencies:

pip install -r requirements.txt

Run the Jupyter Notebook:
jupyter notebook iris_dataset.ipynb

## Future Improvements
Explore ensemble methods (e.g., XGBoost, LightGBM) for better performance.

Perform advanced hyperparameter tuning using RandomizedSearchCV for efficiency.

Investigate interpretability with SHAP or LIME for feature impact.

Deploy the model using Flask or FastAPI.

Perform hyperparameter tuning for better performance.

Deploy the model using Flask or FastAPI.

# Thank You!
