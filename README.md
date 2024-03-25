# SageMaker-Practical-Course

# Info
Sagemaker Study용 으로 사용

# environment setup
```
conda create -n venv_sagemaker_udemy python=3.10
conda activate venv_sagemaker_udemy
conda install -c conda-forge notebook

[//]: # (pip install --upgrade pip)
[//]: # (pip install tensorflow)
conda install -c conda-forge tensorflow
conda install -c conda-forge seaborn
conda install -c conda-forge sagemaker
conda install -c conda-forge boto3
conda install -c conda-forge scikit-learn



```
`conda install -c conda-forge tensorflow` 로 설치시 매우 오래 걸림...



```
conda create -n venv_sagemaker_udemy python=3.10
conda activate venv_sagemaker_udemy
conda install -c conda-forge mamba
mamba install -c conda-forge ipykernel
python -m ipykernel install --user --name venv_sagemaker_udemy --display-name venv_sagemaker_udemy
mamba install -c conda-forge tensorflow
mamba install -c conda-forge seaborn
mamba install -c conda-forge sagemaker
[//]: # (mamba install -c conda-forge boto3)
mamba install -c conda-forge scikit-learn

```
