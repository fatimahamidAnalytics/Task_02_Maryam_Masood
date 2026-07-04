# Task_02_Maryam_Masood
# DecodeLab_Internship
# Data Classification Using AI

## Project Description

This project demonstrates a basic Artificial Intelligence classification task using the Iris Flower Dataset. A Decision Tree Classifier is implemented to classify iris flowers into three different species based on their physical measurements.

The project follows the complete machine learning workflow, including loading the dataset, understanding the data, splitting it into training and testing sets, training the classification model, evaluating its performance, and predicting the class of a new sample.

## Objectives

- Load and understand the Iris dataset.
- Split the dataset into training and testing sets.
- Train a Decision Tree classification model.
- Evaluate the model using performance metrics.
- Predict the species of a new flower sample.

## Features

- Loads the built-in Iris dataset from Scikit-learn.
- Displays dataset information and statistics.
- Splits data into training and testing datasets.
- Trains a Decision Tree Classifier.
- Calculates model accuracy.
- Generates a Classification Report.
- Displays a Confusion Matrix.
- Predicts the class of a new sample.

## Technologies Used

- Python 3
- Scikit-learn
- Pandas

## Dataset

The project uses the **Iris Flower Dataset**, which contains:

- 150 samples
- 3 flower species
  - Setosa
  - Versicolor
  - Virginica
- 4 numerical features:
  - Sepal Length
  - Sepal Width
  - Petal Length
  - Petal Width

## Project Structure

```
Data-Classification-AI/
│── classification.py
│── README.md
```

## Installation

Install the required libraries before running the project.

```bash
pip install pandas scikit-learn
```

## How to Run

1. Download or clone the repository.
2. Open a terminal in the project folder.
3. Run the following command:

```bash
python classification.py
```

## Workflow

1. Load the Iris dataset.
2. Understand the dataset through basic statistics.
3. Split the data into training and testing sets.
4. Train the Decision Tree Classifier.
5. Evaluate the model using:
   - Accuracy Score
   - Classification Report
   - Confusion Matrix
6. Predict the species of a new flower sample.

## Sample Output

```
STEP 1: Load and Understand the Dataset

Shape: 150 rows, 6 columns

STEP 2: Split Data into Training and Testing Sets

Training samples: 120
Testing samples: 30

STEP 3: Apply a Simple Classification Algorithm

Model: Decision Tree Classifier
Accuracy on test set: 96.67%

BONUS: Predict a New Sample

Predicted species: Setosa
```

## Learning Outcomes

This project demonstrates:

- Data loading and preprocessing
- Data exploration
- Train-test splitting
- Supervised machine learning
- Decision Tree Classification
- Model evaluation
- Prediction using trained models

## Conclusion

This project successfully implements a Decision Tree Classifier to classify iris flowers based on their measurements. It provides a simple introduction to supervised machine learning and demonstrates the complete classification process from data preparation to model evaluation and prediction.

## Author

**Fatima Hamid**

Biostatistics Student | Learning Artificial Intelligence and Machine Learning
