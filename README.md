
# Diabetes Classification

This is a university machine learning project where I worked on predicting diabetes using the Pima Indians Diabetes dataset.

## Note
This project was created for educational purposes as part of a university machine learning course. It is not intended to be used as a medical diagnosis tool.

## What I Did

I first loaded and explored the dataset to understand its structure, basic statistics and the number of people with and without diabetes.

Some columns contained zero values that were not realistic for measurements such as glucose, blood pressure, skin thickness, insulin and BMI. I replaced these zero values with missing values and then filled them using the median of each column.

I also created simple visualisations to compare the number of diabetes and non diabetes cases and to see how glucose levels differ between the two groups.

After preparing the data, I separated the features from the target value and split the dataset into training and testing sets.

I used StandardScaler to scale the input features before training the models.

## Models Used

I trained and compared two classification models:

- Logistic Regression
- Random Forest

The results from my run were:

- Logistic Regression Accuracy: 75.32%
- Random Forest Accuracy: 73.38%

I also evaluated the Random Forest model using a classification report and a confusion matrix.

## Technologies Used

- Python
- NumPy
- pandas
- Matplotlib
- scikit-learn
- Jupyter Notebook

## Dataset

The project uses the Pima Indians Diabetes dataset.

The notebook loads the dataset directly from:

https://raw.githubusercontent.com/jbrownlee/Datasets/master/pima-indians-diabetes.data.csv

Because the dataset is loaded directly from the link, no separate dataset file needs to be added to the repository.

## How to Run the Project

First, clone or download the repository.

Install the required libraries:

```bash
pip install -r requirements.txt


