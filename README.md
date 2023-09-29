# BIOT7060
## Machine Learning Workshop - Exploring Small Molecule Bee Toxicity

by [@alexgcsa](https://twitter.com/alexgcsa)

## Colab Notebooks

The material can be accessed via Google Colab Notebooks:
- [Classification colab](https://colab.research.google.com/github/carlosmr12/mlwk2023/blob/master/lecture1_classification.ipynb)


## Local installation

Alternatively, if you want to run it locally, we suggest you use [anaconda](https://docs.anaconda.com/free/anaconda/install/) (or [miniconda](https://docs.conda.io/en/latest/miniconda.html)) to manage a virtual environment and install dependencies.


### First, create an environment with the following command:

```bash
$ conda create -n workshop_ml
```

### Then, install dependencies via pip:


```bash
$ conda activate workshop_ml

$ conda install python=3.10

$ pip install -r requirements.txt
```

### If you need to run under this environment at any time, use the following command to activate it and open the notebook:

```bash
$ conda activate workshop_ml

$ jupyter notebook
```

