# BIOT7060
## Machine Learning Workshop - Predicting Patient Diabetes with Demographics and Medical Information

by [@alexgcsa](https://twitter.com/alexgcsa)

## Colab Notebooks

The material can be accessed via Google Colab Notebooks:
- [Classification Colab - Part 1](https://colab.research.google.com/github/alexgcsa/ml_workshop_Oct2023/blob/master/BIOT7060_mlw_p1_v2.ipynb)
- [Classification Colab - Part 2](https://colab.research.google.com/github/alexgcsa/ml_workshop_Oct2023/blob/master/BIOT7060_mlw_p2_v5.ipynb)


## Local installation

Alternatively, if you want to run it locally, we suggest you use [Anaconda](https://docs.anaconda.com/free/anaconda/install/) (or [Miniconda](https://docs.conda.io/en/latest/miniconda.html)) to manage a virtual environment and install dependencies.


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

