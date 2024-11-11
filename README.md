# Credit Card Fraud Detection Model

This repository contains the code and dataset used for a project focused on detecting fraudulent transactions in credit card data. The project leverages both supervised and unsupervised learning techniques, particularly Random Forest, XGBoost, Autoencoder, and One-Class SVM models, to identify fraudulent transactions.

## Project Overview

Credit card fraud is a significant issue faced by financial institutions worldwide. The primary goal of this project is to develop models capable of detecting fraudulent transactions using both supervised and unsupervised learning approaches. The dataset used contains transactions labeled as either fraudulent or non-fraudulent, allowing for both classification and anomaly detection methods to be applied.

## Key Findings

1. **Supervised Learning Models:**
   - **Random Forest** and **XGBoost** both achieved high accuracy, with Random Forest slightly outperforming XGBoost in precision and recall.
   
2. **Unsupervised Learning Models:**
   - **Autoencoder** showed promise in detecting anomalies but required careful tuning to avoid high false-positive rates.
   - **One-Class SVM** achieved a balance between precision and recall, but hyperparameter tuning was not feasible due to time inefficiency.

The final models were evaluated based on accuracy, precision, recall, F1-score, and ROC AUC score.

## Project Structure

The project is structured as follows:

- **data/**: Contains the dataset used for model training and testing.
- **notebooks/**: Jupyter notebooks with the complete code for training and evaluating the models.
- **output/**: Generated output files including predictions and evaluation metrics.
- **requirements.txt**: Python dependencies required to run the project.
- **LICENSE**: MIT License for the project.

## Installation

To set up the project, clone the repository and install the required dependencies:

    ```bash
    git clone <repository-url>
    cd <repository-directory>
    pip install -r requirements.txt

## Usage

Run the notebooks in the notebooks/ directory to train and evaluate the models. It is recommended to use Google Colab for running the notebooks.

## Results

The models were evaluated using various metrics, including accuracy, precision, recall, F1-score, and ROC AUC. Detailed results can be found in the notebooks and output files.
