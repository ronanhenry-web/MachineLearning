Projet Python, découvrir le concept du ML avec kNN, régression et classification supervisée

Tuto installation :

# Création d'un environnement python dédié au cours de machine learning: ml

La solution conseillée: utilisation de conda
https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html


Création d'environnement
-> conda create -n ml python=3.11
-> conda env list

Se placer dans l'environnement
-> conda activate ml
(ml) ➜  ~

Installation de librairies, par exemple ISLP
-> pip install ISLP

install jupyter lab
https://jupyterlab.readthedocs.io/en/stable/getting_started/installation.html
-> conda install -c conda-forge jupyterlab


Ajout de l'environnement à Jupyter
Il faut que Jupyter soit installé
cf "method 2" dans
https://towardsdatascience.com/get-your-conda-environment-to-show-in-jupyter-notebooks-the-easy-way-17010b76e874
-> conda install ipykernel
-> ipython kernel install --user --name=ml

Lancer jupyter lab
-> jupyter lab
