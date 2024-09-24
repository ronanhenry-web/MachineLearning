# Machine Learning Project

Discovering the concept of Machine Learning with k-NN, regression, and supervised classification

## Getting Started

The project was created using Miniconda. To get it running, follow these steps :

### Creating a dedicated Python environment for the machine learning: ml

Recommended solution: use conda
https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html

Create the environment :
```bash
conda create -n ml python=3.11
```
```bash
conda env list
```

Activate the environment :
```bash
conda activate ml
```
```bash
(ml) ➜  ~
```

Install libraries, for example, ISLP :
```bash
pip install ISLP
```

Install jupyter lab (https://jupyterlab.readthedocs.io/en/stable/getting_started/installation.html) :
```bash
conda install -c conda-forge jupyterlab
```

Add the environment to Jupyter (Jupyter must be installed) :

cf "method 2" in (https://towardsdatascience.com/get-your-conda-environment-to-show-in-jupyter-notebooks-the-easy-way-17010b76e874)

```bash
conda install ipykernel
```
```bash
ipython kernel install --user --name=ml
```

Start Jupyter Lab :
```bash
jupyter lab
```

## Sources & Tools

<a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a>
