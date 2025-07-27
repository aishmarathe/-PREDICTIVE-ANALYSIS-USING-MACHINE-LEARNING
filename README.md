# -PREDICTIVE-ANALYSIS-USING-MACHINE-LEARNING
* COMPANY: CODTECH IT SOLUTIONS
* NAME: AISHWARYA ZUNJAR MARATHE
* INTERN ID: CITS0D676
* DOMAIN: DATA ANALYTICS
* DURATION: 6 WEEKS
* MENTOR: NEELA SANTOSH


---

# Animal Health Prediction using KNN

## Overview

This project aims to help predict the disease in animals based on a few basic health inputs. It uses a Machine Learning model (K-Nearest Neighbors) to make accurate predictions using a dataset of animal health records.

## Features

* Takes user input for:

  * Breed
  * Temperature
  * Age
  * Symptom 1
  * Symptom 2
  * Symptom 3
* Predicts the most likely disease
* Simple, user-friendly input process
* Trained using the K-Nearest Neighbors (KNN) classification algorithm

## Technologies Used

* Python
* Pandas
* Scikit-learn
* Jupyter Notebook

## Dataset

The dataset contains more than 1,500 animal health records including:

* Animal breed
* Temperature
* Age
* Various symptoms
* Diagnosed disease

The data was preprocessed and used to train the KNN model for prediction.

## How It Works

1. The user provides input about the animal's breed, temperature, age, and symptoms.
2. The input is preprocessed and converted into a format suitable for the model.
3. The trained KNN model analyzes the input and predicts the most likely disease.

## Steps to Run

1. Clone this repository
2. Install required libraries:

   ```
   pip install pandas scikit-learn
   ```
3. Open the Jupyter Notebook and run all the cells
4. Enter the animal's details and view the predicted disease

## Model Accuracy

* The model achieved over **92% accuracy** after selecting key features and optimizing the training process.
* Processing time was reduced by over 30% with feature selection.

## Future Work

* Add a simple web interface for easier input
* Include more symptoms and disease types
* Use deep learning for more complex predictions

