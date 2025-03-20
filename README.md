# Prices_Prediction-system

**Overview**

The Prices Predictor System is a machine learning-based application designed to analyze and predict prices based on various features. The system utilizes data preprocessing, feature engineering, and model evaluation to generate accurate price predictions.

Features

Data ingestion and preprocessing

Exploratory data analysis (EDA)

Feature engineering and selection

Model training and evaluation

Deployment of the trained model for inference

Required Tools & Platforms

Operating System: Windows 10 (Preferred)

Python Version: 3.10

Download from: Python Official Website

IDE: Visual Studio Code (Recommended)

Download from: VS Code Official Website

Required Python Modules

Install the required dependencies from requirements.txt using the following command:

The key dependencies include:

Flask

Pandas

NumPy

Scikit-learn

Matplotlib

Seaborn

Refer to requirements.txt for the complete list.

ZenML Installation & Setup

To run this project, you need to install and configure ZenML.

1. Install ZenML

Follow the official installation guide: ZenML Installation

2. Create a Virtual Environment

Once you download the source code, create a virtual environment by following this guide: Virtual Environment Guide

3. Activate the Virtual Environment

Once the virtual environment is activated, run the following command:

4. Install ZenML Integrations

If you are running the run_deployment.py script, you will need to install some integrations using ZenML:

5. Configure the ZenML Stack

The project can only be executed with a ZenML stack that has an MLflow experiment tracker and model deployer as components. Configure the new stack with the following commands:

Project Structure

Setup Instructions

1. Clone the Repository

2. Create a Virtual Environment

Activate the environment:

Windows:

Mac/Linux:

3. Install Dependencies

Run the following command to install all dependencies:

Execution Steps

Run the Pipeline

To execute the main pipeline, run:

Run Deployment

To deploy the model for predictions, execute:

Make Predictions

To make predictions using the trained model, run:
