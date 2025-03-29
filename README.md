# Cancer-Prediction-a-deep-learning-project

# workflow

1.Update config.yaml
2.Update params.yaml
3.Update the entity
4.Update the configuration manager in src config
5.Update the components
6.Update the pipeline
7.Update the main.py
8.Update the dvc.yaml

## create virtual enviroment

```bash
conda create -n chest python=3.8 -y
```

```bash
conda activate chest
```

```bash
pip install -r requirements.txt
```

```bash
export MLFLOW_TRACKING_URI=https://dagshub.com/banerjeeishita2005/Cancer-Prediction-a-deep-learning-project.mlflow

export MLFLOW_TRACKING_USERNAME=banerjeeishita2005

export MLFLOW_TRACKING_PASSWORD=ed44259b0c674d8b0a61fb6ddec192c428016825
```

DVC cmd
dvc init
dvc repro
dvc dag
About MLflow & DVC

MLflow

Its Production Grade
Trace all of your expriements
Logging & taging your model

DVC

Its very lite weight for POC only
lite weight expriements tracker
It can perform Orchestration (Creating Pipelines)

# Policy:

1. AmazonEC2ContainerRegistryFullAccess

2. AmazonEC2FullAccess
# Create ECR repo to store/save docker image
050451382029.dkr.ecr.eu-north-1.amazonaws.com/chest