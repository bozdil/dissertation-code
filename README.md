# Developing Predictive Analytics for Customer Churn and Retention: A Machine Learning Approach Using Python for Mobile Apps

This repository stores various models, their training data, deployment code and web application for analysing customer churn prediction.

There are 4 datasets used:

- Cell2cell
- mobilegame
- streaming
- Telco

All of the above datasets are acquired from Kaggle and in folders for each, there is cleaned/preprocessed training and validation data for ML applications.
In addition, there are models that are selected and generated using AWS Sagemaker.

Each jupyter notebooks in the repository named `sagemaker-deploy.ipynb` can be used to run and deploy the models trained on the data into AWS SageMaker Endpoints.

`webapp` folder hosts a small static web application configured to work with `Telco` database and connects to AWS Endpoint for TabTransformers for real time inference results.

More information and details can be found at the Dissertation itself. 

_Note: It will be uploaded here later_