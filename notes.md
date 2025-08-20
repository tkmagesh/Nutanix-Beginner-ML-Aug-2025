# AI/ML Beginner

## Magesh Kuppan
- tkmagesh77@gmail.com

## Schedule
| What | When |
| ---- | ---- |
| Session - 01 | 1:50 hrs |
| Tea Break | 20 mins |
| Session - 02 | 1:50 hrs |

## Repository
- https://github.com/tkmagesh/Nutanix-Beginner-ML-Aug-2025


## Prerequistes
- Python
- Visual Studio Code
    - Jupyter plugin (https://marketplace.visualstudio.com/items/?itemName=ms-toolsai.jupyter) 

## Setup for experimenting
### Local
1. Create a virtual environment
```shell
python -m venv ml_practice
```

2. Activate the virtual environment
```shell
source ml_practice/bin/activate
```

3. Install the packages
```shell
pip install numpy pandas scikit-learn matplotlib seaborn ipykernel notebook
```

4. Create a ipykernel for jupyter notebook
```shell
python -m ipykernel install --user --name=nutanix_ml_kernel
```

5. Using Notebook

5.1 Using Browser 
```shell
jupyter notebook
```

5.2 Using the Jupyter Extension in VSCode
https://marketplace.visualstudio.com/items/?itemName=ms-toolsai.jupyter

### Cloud
- https://colab.research.google.com/

## What is Machine Learning?
### Predicting the future using the understanding of the Past

## ML Terms
- features, independent variables, attributes (inputs)
- target, dependent variable (output)
- observation (1 row)
- samples (dataset OR collection of observations)
- Model - encapsulates the relationship among the features and target (incase of supervised) OR among the features (incase of unsupervised)
- ML Algorithm => creates a model by analysing the features & target

## Steps
1. Load the data
2. Identify the features & target (regression)
3. Split the dataset into training set & test set (Hold out cross validation technique)
4. Train the model using the training set
5. Test the model using the test set
6. Evaluate the performance (accurancy in prediction for supervised learning) of the model