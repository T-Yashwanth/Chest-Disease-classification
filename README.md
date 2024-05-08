# Chest-Disease-classification

## How to Run

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
python app.py
```

## Workflows

1. Update config.yaml
2. Update params.yaml
3. Update the entity
4. Update the configuration manager in src config
5. Update the components
6. Update the pipeline 
7. Update the main.py
8. Update the dvc.yaml 

### MLflow dags connections uri

```bash
MLFLOW_TRACKING_URI=<https>\
MLFLOW_TRACKING_USERNAME=<>\
MLFLOW_TRACKING_PASSWORD=<>\
python script.py
```


### RUN from bash terminal

```bash
export MLFLOW_TRACKING_URI=https://dagshub.com/T-Yashwanth/Chest-Disease-classification.mlflow

export MLFLOW_TRACKING_USERNAME=T-Yashwanth

export MLFLOW_TRACKING_PASSWORD=33add6eb0c8a2f39f9671d6ba0f49adfd5298099

```

### DVC cmd

1. dvc init
2. dvc repro
3. dvc dag