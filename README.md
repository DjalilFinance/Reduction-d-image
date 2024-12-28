Traitement d'images - Vision par ordinateur


Description

Ce projet implémente des techniques avancées de traitement d'images et de réduction de dimensionnalité pour des applications de vision par ordinateur. Il combine des méthodes comme t-SNE optimisé avec CUDA pour accélérer 

les calculs, et utilise des benchmarks pour évaluer les performances.


Structure du projet

t_sne_bhcuda/ : Implémentation optimisée de t-SNE en utilisant CUDA pour accélérer les calculs.

Benchmark.ipynb : Notebook contenant des benchmarks pour évaluer les performances des approches.

dimensionality_reduction.ipynb : Notebook explorant différentes techniques de réduction de dimensionnalité.

utils.py : Fonctions auxiliaires pour le traitement des données et la visualisation.

conda.yaml : Fichier YAML pour configurer l'environnement Conda pour les dépendances.

Fonctionnalités clés

Réduction de dimensionnalité : Implémentation de t-SNE optimisé avec CUDA pour gérer de grands ensembles de données.

Benchmarks : Évaluation des performances des algorithmes pour différentes tailles de données.

Traitement d'images : Prétraitement et réduction de dimensionnalité pour des applications de vision par ordinateur.

Optimisation GPU : Utilisation de CUDA pour accélérer les calculs.

Installation

Clonez ce dépôt :



bash

Copier le code

git clone https://github.com/ton_profil/Traitement-d-images-Vision-par-ordinateur.git

cd Traitement-d-images-Vision-par-ordinateur

Configurez l’environnement Conda :


bash

Copier le code

conda env create -f conda.yaml

conda activate vision_env

Compilez les fichiers CUDA :


bash

Copier le code

nvcc -o t_sne_bhcuda/t_sne_gpu t_sne_bhcuda/t_sne_gpu.cu

Utilisation

Notebook Benchmark.ipynb :

Lancer le notebook pour comparer les performances des algorithmes.


Notebook dimensionality_reduction.ipynb :

Explorez les techniques de réduction de dimensionnalité appliquées à des données d'image.


Technologies utilisées

Langages : Python, CUDA.

Frameworks : Jupyter Notebook, NumPy.

Bibliothèques : t-SNE, matplotlib.

Contributeurs

SALAH BEY ABDELDJALIL
