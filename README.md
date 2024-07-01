# Kidney_Disease-Classification-Deep-Learning-Project



## Workflows
1.Update config.yaml
2.Update secrets.yaml [Optional]
3.Update params.yaml
4.Update the entity
5.Update the configuration manager in src config
6.Update the components
7.Update the pipeline
8.Update the main.py
9.Update the dvc.yaml
10.app.py


# How to run?

### STEPS:

Clone the repository

``` bash
https://github.com/Abimael-Sacker/Kidney_Disease-Classification-Deep-Learning-Project
```

### STEP 01-Create a conda enviroment after opening the repository
```bash
conda create -n cnncls python=3.8 -y
```

```bash
conda activate cnncls
```
### STEP 02-Install the requirements

```bash
pip install -r requirements.txt
```
### DAGSHUB
[dagshub](https://dagshub.com/)

import dagshub
dagshub.init(repo_owner='Abimael-Sacker', repo_name='Kidney_Disease-Classification-Deep-Learning-Project', mlflow=True)

import mlflow
with mlflow.start_run():
  mlflow.log_param('parameter name', 'value')
  mlflow.log_metric('metric name', 1)

Run this to export as env variables:
```bash


export MLFLOW_TRACKING_URI=https://dagshub.com/Abimael-Sacker/Kidney_Disease-Classification-Deep-Learning-Project.mlflow

export MLFLOW_TRACKING_USERNAME=Abimael-Sacker

export MLFLOW_TRACKING_PASSWORD=Razernaga15$

```