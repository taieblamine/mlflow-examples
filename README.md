## Setup Environment

### Install minconda

```bash
mkdir -p ~/miniconda3
wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh -O ~/miniconda3/miniconda.sh
bash ~/miniconda3/miniconda.sh -b -u -p ~/miniconda3
rm ~/miniconda3/miniconda.sh
```

### Activate miniconda

```bash
source ~/miniconda3/bin/activate
```

### Activate miniconda on all shells

```bash
conda init --all
```

### Create conda environment

```bash
conda create -n mlflow-env python==3.12
```

### Activate environment

```bash
conda activate mlflow-env
```

## Install mlflow package

```bash
pip install mlflow
```

## MLflow UI

```bash
mlflow ui --port 5000
```

## Model Registry Tutorial

https://www.mlflow.org/docs/latest/ml/model-registry/tutorial/


## MLFlow for Deep Learning

```bash
pip install mlflow torch torchvision
```