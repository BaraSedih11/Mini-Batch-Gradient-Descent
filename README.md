<div align=center>
  
  ![Mini-Batch_Gradient_Descent](https://github.com/BaraSedih11/Mini-Batch-Gradient-Descent/assets/98843912/8fa085fe-8cef-44fd-9553-92cb59b631ac)


   ![GitHub repo size](https://img.shields.io/github/repo-size/BaraSedih11/mini-batch-gradient-descent) ![GitHub repo file count (file type)](https://img.shields.io/github/directory-file-count/BaraSedih11/mini-batch-gradient-descent) [![Python Version](https://img.shields.io/badge/python-3.8-blue)](https://www.python.org/downloads/release/python-380/)
[![Pip Version](https://img.shields.io/badge/pip-21.0-orange)](https://pypi.org/project/pip/21.0/)
 ![GitHub last commit (branch)](https://img.shields.io/github/last-commit/BaraSedih11/mini-batch-gradient-descent/main)
[![Version](https://img.shields.io/badge/version-v1.0.0-blue)](https://github.com/BaraSedih/mini-batch-gradient-descent/releases/tag/v1.0.0)
[![Contributors](https://img.shields.io/github/contributors/BaraSedih11/mini-batch-gradient-descent)](https://github.com/BaraSedih11/mini-batch-gradient-descent/graphs/contributors)
![GitHub pull requests](https://img.shields.io/github/issues-pr-raw/BaraSedih11/mini-batch-gradient-descent)
  
</div>

This repository contains an implementation of Mini-Batch Gradient Descent, a variant of the Gradient Descent optimization algorithm often used in machine learning and deep learning. Mini-Batch Gradient Descent is particularly useful when dealing with large datasets, as it updates the model's parameters using a subset of the training data at each iteration.

## Overview

Gradient Descent is a popular optimization algorithm used to minimize the loss function in machine learning models by iteratively moving towards the minimum of the loss function. Mini-Batch Gradient Descent is a variation of this algorithm where instead of computing the gradient of the entire dataset (Batch Gradient Descent) or just one sample (Stochastic Gradient Descent), it computes the gradient based on a randomly selected subset of the training data (mini-batch). This approach combines the advantages of both Batch Gradient Descent and Stochastic Gradient Descent, making it suitable for large-scale datasets.

This repository provides a simple implementation of Mini-Batch Gradient Descent in Python, along with examples demonstrating its usage.

## Contents

- `Mini-Batch-Gradient-Descent.ipynb`: Jupyter Notebook containing the implementation of polynomial regression using Python.
- `bmi_and_life_expectancy.csv`: Sample dataset used in the notebook for demonstration purposes.
- `README.md`: This file providing an overview of the repository.


## Requirements
To run the code in the Jupyter Notebook, you need to have Python installed on your system along with the following libraries:

* NumPy
* pandas
* scikit-learn
* matplotlib
You can install these libraries using pip:

```bash
pip install numpy pandas scikit-learn matplotlib
```

## Usage

1. Clone this repository to your local machine:

```bash
git clone https://github.com/BaraSedih11/Mini-Batch-Gradient-Descent.git
```

2. Navigate to the repository directory:

```bash
cd Mini-Batch-Gradient-Descent
```

3. Open and run the Jupyter Notebook `Mini-Batch-Gradient-Descent.ipynb` using Jupyter Notebook or JupyterLab.

4. Follow along with the code and comments in the notebook to understand how polynomial regression is implemented using Python.


## Acknowledgements

- [scikit-learn](https://scikit-learn.org/): The scikit-learn library for machine learning in Python.
- [NumPy](https://numpy.org/): The NumPy library for numerical computing in Python.
- [pandas](https://pandas.pydata.org/): The pandas library for data manipulation and analysis in Python.
- [matplotlib](https://matplotlib.org/): The matplotlib library for data visualization in Python.
