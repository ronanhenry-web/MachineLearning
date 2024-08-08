# Projet Machine Learning

Découvrir le concept du MachineLearning avec kNN, régression et classification supervisée

## Démarrer

Le projet a été créé sous Miniconda, pour le démarrer suivre les étapes suivantes.

### Création d'un environnement python dédié au cours de machine learning: ml

La solution conseillée : utilisation de conda
https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html

Création d'environnement :
```bash
conda create -n ml python=3.11
```
```bash
conda env list
```

Se placer dans l'environnement :
```bash
conda activate ml
```
```bash
(ml) ➜  ~
```

Installation de librairies, par exemple ISLP :
```bash
pip install ISLP
```

Install jupyter lab (https://jupyterlab.readthedocs.io/en/stable/getting_started/installation.html) :
```bash
conda install -c conda-forge jupyterlab
```

Ajout de l'environnement à Jupyter, il faut que Jupyter soit installé :

cf "method 2" dans (https://towardsdatascience.com/get-your-conda-environment-to-show-in-jupyter-notebooks-the-easy-way-17010b76e874)

```bash
conda install ipykernel
```
```bash
ipython kernel install --user --name=ml
```

Lancer jupyter lab :
```bash
jupyter lab
```

## Sources & Outils

<a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a>
