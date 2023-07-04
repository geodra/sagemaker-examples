# AI/ML on SageMaker Notebooks
This repository contains a collection of useful Jupyter notebooks focused on Artificial Intelligence (AI) and Machine Learning (ML) workflows using Amazon SageMaker. SageMaker is a fully managed service provided by Amazon Web Services (AWS) that enables developers and data scientists to build, train, and deploy machine learning models at scale.

The notebooks provided here serve as practical examples and tutorials to help you get started with AI/ML on SageMaker, covering a range of topics including data preprocessing, model training, hyperparameter tuning, model deployment, and more. These notebooks are designed to be interactive, allowing you to run the code cells, modify parameters, and experiment with different configurations.

## SageMaker Notebooks - No space left on device [Amazon SageMaker]

1. Open a terminal
2. Run `df -h` all voulme size is under `/home/ec2-user/SageMaker`
3. Need to change default linux cache location `/home/ec2-user/.cache`
4. Create new directory `mkdir /home/ec2-user/SageMaker/cache`
5. Run on the terminal `export XDG_CACHE_HOME="/home/ec2-user/SageMaker/cache"`

## Terminal commands to check:
1. RAM memory: `free -h`
2. GPU memory: `nvidia-smi`
3. 