# Machine Learning Models Comparison for Diabetes Prediction

This repository presents a comprehensive comparison of nine machine learning models applied to the task of predicting diabetes from a dataset containing medical and demographic data. The goal is to evaluate the performance of each model based on their accuracy in predicting diabetes status, providing insights into which models are most effective for this specific use case.

## Models and Parameters

The comparison includes the following models with specified parameters:

The following table summarizes the configuration parameters used for each machine learning model in this comparison:

| Model                         | Parameters                                                                                                                           |
| ----------------------------- | ------------------------------------------------------------------------------------------------------------------------------------ |
| **XGBoost**             | colsample_bytree: 0.9`<br>`gamma: 0.1`<br>`learning_rate: 0.2`<br>`max_depth: 7`<br>`n_estimators: 300`<br>`subsample: 0.9 |
| **Gradient Boosting**   | learning_rate: 0.2`<br>`max_depth: 5`<br>`n_estimators: 300                                                                      |
| **AdaBoost**            | learning_rate: 1`<br>`n_estimators: 200                                                                                            |
| **Logistic Regression** | C: 0.1`<br>`penalty: l2`<br>`solver: liblinear                                                                                   |
| **Decision Tree**       | criterion: entropy`<br>`max_depth: None`<br>`min_samples_leaf: 2`<br>`min_samples_split: 5                                     |
| **KNN**                 | metric: manhattan`<br>`n_neighbors: 3`<br>`weights: distance                                                                     |
| **Perceptron**          | alpha: 0.0001`<br>`max_iter: 1000`<br>`penalty: l2                                                                               |
| **Random Forest**       | criterion: entropy`<br>`max_depth: None`<br>`min_samples_split: 2`<br>`n_estimators: 500                                       |
| **Naïve Bayes**        | var_smoothing: 10.0                                                                                                                  |

Each model was carefully tuned with the above parameters to optimize performance for the task of diabetes prediction.

## About the Dataset

The Diabetes Prediction Dataset encapsulates a wide range of information, including:

- **Age**: Patient's age in years.
- **Gender**: Patient's gender (Male/Female/Other).
- **BMI**: Body Mass Index, a key indicator of health.
- **Hypertension**: Presence of hypertension (1: Present, 0: Absent).
- **Heart Disease**: Presence of any heart disease (1: Present, 0: Absent).
- **Smoking History**: Smoking behavior of the patient.
- **HbA1c Level**: Hemoglobin A1c level indicating average blood sugar over the past 3 months.
- **Blood Glucose Level**: Fasting blood glucose level.

This dataset is primarily aimed at:

- Healthcare professionals for early identification of high-risk patients.
- Researchers analyzing the impact of lifestyle and genetic factors on diabetes.


## Getting Started (In-Progress)

### Prerequisites

Ensure you have Python 3.x installed along with the following libraries:

* pandas
* numpy
* scikit-learn
* xgboost

### Installation

Clone this repository and install the required Python packages:



## Running the Models

To run the model comparison, navigate to the project directory and execute:


## Results (In-Progress)

In-Progress

## License (In-Progress)

In-Progress

## Acknowledgments (In-Progress)

* dataset, libraries used.
* contributors.
