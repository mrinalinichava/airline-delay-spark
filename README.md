# airline-delay-spark


# Spark MLlib on Airline Delay Prediction

## Overview
This project utilizes Apache Spark MLlib to predict flight delays using the Airlines dataset. The aim is to determine the likelihood of a flight being delayed based on scheduled departure times and other relevant features.

## Dataset
The dataset consists of 539,383 instances and 8 different features and is used to predict flight delays. It is available for download at: [Kaggle Airlines Dataset](https://www.kaggle.com/datasets/jimschacko/airlines-dataset-to-predict-a-delay).

## Objectives
- **Data Preprocessing**: Clean and prepare the dataset for machine learning models.
- **Feature Engineering**: Enhance model performance by extracting and selecting significant features.
- **Algorithm Selection**: Compare at least four different machine learning algorithms.
- **Model Training**: Implement k-fold cross-validation during training to optimize model parameters.
- **Model Evaluation**: Assess model performance using metrics such as accuracy, precision, recall, F1-score, and ROC curves.

## Technologies Used
- **Apache Spark**: Utilized for its powerful in-memory computing capabilities, ideal for processing large datasets.
- **MLlib**: Spark's machine learning library used for model building and evaluation.
- **Python**: The primary programming language used with PySpark for script execution.

## Files in the Repository
- `Airline_Prediction_Spark.ipynb`: Jupyter notebook containing the full code, from data preprocessing to model evaluation.
- `requirements.txt`: Lists all Python libraries required to run the notebook.

## Setup and Installation
Ensure you have the following installed:
- Python 3.8+
- Apache Spark 3.0+
- Find the detailed steps to set up your environment in the `setup.md` file included in this repository.

## Running the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/mrinalinichava/airline-delay-spark.git
