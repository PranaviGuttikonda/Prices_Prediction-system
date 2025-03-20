# Prices_Prediction-system

**Overview**

The Prices Predictor System is a machine learning-based application designed to analyze and predict prices based on various features. The system utilizes data preprocessing, feature engineering, and model evaluation to generate accurate price predictions.

**Features:** 

● Data ingestion and preprocessing

● Exploratory data analysis (EDA)

● Feature engineering and selection

● Model training and evaluation

● Deployment of the trained model for inference

**Required Tools & Platforms:**

● Operating System: Windows 10 (Preferred)

● Python Version: 3.10.11 (Latesr versions. such as Python 3.13, are not compatible due to the issues with installing dependencies from requirements.txt)

  ● Download from: https://www.python.org/downloads/
  
● IDE: Visual Studio Code (Recommended)

  ● Download from: https://code.visualstudio.com/download

**Required Python Modules**

Install the required dependencies from requirements.txt using the following command:

The key dependencies include:

● Click: For creating command-line interfaces

● Matplotlib: For data visualization

● MLflow: For managing machine learning workflows

● MLflow_skinny: A lightweight version of MLflow

● NumPy: For numerical operations

● Pandas: For data manipulation and analysis

● Scikit-learn: For machine learning algorithms

● Seaborn: For statistical data visualization

● Statsmodels: For statistical modeling

● ZenML: For MLOps pipelines and deployments 

Refer to requirements.txt for the complete list.


**ZenML Installation & Setup**

To run this project, you need to install and configure ZenML.

**1. Install ZenML**

Follow the official installation guide: **ZenML Installation**

**2. Create a Virtual Environment**

Once you download the source code, create a virtual environment by following this guide: **Virtual Environment Guide**

**3. Activate the Virtual Environment**

Once the virtual environment is activated, install the dependecies

**4. Install ZenML Integrations**

If you are running the **run_deployment.py** script, you will need to install some integrations using ZenML

**5. Configure the ZenML Stack**

Set up the ZenML stack with the following commands

The project can only be executed with a ZenML stack that has an MLflow experiment tracker and model deployer as components. Configure the new stack with the following commands:

**Project Structure**

**Setup Instructions**

1. Clone the Repository

2. Create a Virtual Environment using:
   
    **python -m venv venv (Windows)**
   
    **python3 -m venv venv (Mac/Linux)**
   
   Activate the environment:
   
     Windows:
         **venv\Scripts\activate**
      Mac/Linux:
         **source venv/bin/activate**
   
3. Install Dependencies
   
      Run the following command to install all dependencies:

        **pip install -r requirements.txt**

**Execution Steps**

**Run the Pipeline**

To execute the main pipeline, run:

  **python run_pipeline.py**
  
**Run Deployment**

To deploy the model for predictions, execute:

  **python run_deployment.py**
  
**Make Predictions**

To make predictions using the trained model, run:

  **python make_predictions.py**

**Note:** This project setup is only compatible with **Python 3.10** due to dependency compatiblity issues

