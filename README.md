# SageMaker ML End-to-End

This project demonstrates an end-to-end machine learning workflow using Amazon SageMaker Studio and MLflow for experiment tracking. It leverages various SageMaker features to build, train, and deploy a machine learning model.

## Project Structure

1. **Setup** (`0-setup.ipynb`)
   - Initial configuration and environment setup

2. **Preprocessing** (`1-preprocessing.ipynb`)
   - Data preprocessing using SageMaker Processing Jobs
   - Integration with MLflow for experiment tracking

3. **Training** (`2-training.ipynb`)
   - Model training using SageMaker Training Jobs

4. **Test and Deploy** (`3-test-and-deploy.ipynb`)
   - Model evaluation and testing
   - Deployment using SageMaker endpoints

5. **Pipeline** (`4-pipelines.ipynb`)
   - Building an end-to-end ML pipeline using SageMaker Pipelines


## Key Features

- Utilizes SageMaker Studio for a unified ML development environment
- Implements MLflow for experiment tracking and model versioning
- Demonstrates the use of SageMaker Processing Jobs for data preprocessing
- Showcases SageMaker Training Jobs with hyperparameter tuning
- Illustrates model deployment and testing using SageMaker endpoints
- Builds an automated ML pipeline using SageMaker Pipelines
