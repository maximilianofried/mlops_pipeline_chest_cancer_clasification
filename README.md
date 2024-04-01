# MLOps Pipeline for Chest Cancer Classification

This project involves the development of a deep learning model for analyzing images to classify chest cancer.

## Problem Statement

The objective of this project is to develop a deep learning model that can accurately classify chest cancer from images. Leveraging deep learning techniques, we aim to provide a reliable tool for medical professionals to assist in diagnosing chest cancer.

## Data

The dataset used for this project contains a collection of chest X-ray images labeled with binary classifications indicating the presence or absence of cancerous cells.

- Source: [Provide Data Source]

## Solution

Our solution involves building and training a convolutional neural network (CNN) model to learn from the provided chest X-ray images and classify them into cancerous and non-cancerous categories.

### Workflow

1. **Data Ingestion**: Preprocess the data and prepare it for training.
2. **Model Training**: Train the CNN model using the preprocessed data.
3. **Model Evaluation**: Evaluate the trained model's performance on a separate test dataset.
4. **Model Deployment**: Deploy the trained model for inference in production environments.

### Python Requirements

Ensure you have the necessary Python packages installed by running:
```bash
pip install -r requirements.txt
```

### DVC (Data Version Control)
DVC is used for pipeline tracking and versioning. It helps manage the data and model artifacts efficiently throughout the machine learning lifecycle.

### MLflow
MLflow is integrated into the project for experiment tracking and model management. It provides a comprehensive platform for managing the machine learning lifecycle, including experimentation, reproducibility, and deployment.

### Continuous Integration/Continuous Deployment (CI/CD)
The project utilizes GitHub Actions for CI/CD. Ensure GitHub Actions workflows are set up accordingly for automated build, test, and deployment processes.

### AWS Deployment
For continuous deployment, the project leverages AWS services such as ECR (Elastic Container Registry), EC2 (Elastic Compute Cloud), and Docker for containerization.

### References
- [DVC](https://dvc.org/)
- [MLflow](https://mlflow.org/)


### License
This project is licensed under the MIT License.
