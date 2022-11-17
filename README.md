# MLOps-with-MLflow
In this project, I aim at developing an end-to-end Machine Learning project, from problem formulation to model deployment and monitoring in production environment. MLflow will be utilized for experiment tracking and model registry managment, for containerization of the model, Docker will be utilizied. A machine learning model goes throgh different phases in its lifecycle from requirements elicitation to monitoring in production. There are varius industry standarts describing the exact phases and their outcomes, such as CRIISP-DM, Microsft Team Data Science Process and etc. Nonetheless, a typical machine learning process involves business understanding, requiremnts eliciation, explorotary data analysis, data transformation, feature engineering, modeling, experiment tracking, evaluation, productionaizing, and at last monitoring and continuos improvements.
## Sections:
- Data Science Process
- MLflow Introduction
- Business Understanding
- Data Understanding
- Data Transformation & Feature Engineering
- Experiement Tracking
- Evaluation
- Deployment & Productionaizing 
- Monitoring

## Data Science Process
There are various standarts in the industry which describes data science process. The CRoss Industry Standard Process for Data Mining (CRISP-DM) is one of those process models that serves as the base for a data science process. The CRISP-DM process is a widely utilezed to manage the lifecycle of data science / machine learning projects. The below diagram depicts 6 main phases that any data science project goes through:

| ![CRSIP-DM](https://www.datascience-pm.com/wp-content/uploads/2021/02/CRISP-DM.png) |
|:--:|
| <b>CRISP-DM Diagram. Source: Data Science Process Aliance</b>|

## MLflow Introduction
The machine learning (ML) life cycle encompases many phases. In this project, I will utilize open source platform called MLflow that focuses on reproducibility, training, and deployment. With clients in Python and Java and a REST API, it is built on an open interface architecture and compatible with any platform or language. Another significant advantage that an ML developer may take use of using MLflow is scalability.

It is often the case that the tools and paradims used by data scientist who train the machine learning models and machine learning engineers who scale the machine learning system up and productionize it differ significantly due to the nature of their work. Hence, often there occurs friction between data science and engineering teams when the models goes into production. Many companies have developed their in-house tools in order to alleviate the friction and provide one solution which can be used from model development until model production. MLflow is one of such tools which is developed by Databricks and opensourced as a ML framework.

Getting a working production environment and ensuring that the training code is usable and reliable requires a significant amount of code writing. One of MLflow's main goals is to support building ML systems and projects. In the following sections, we will try to build a project in a way to support both rebustness and reliability and at the same time get a model which is deployable using Docker containers.
