#  Prévision des Ventes

##  Objectif du projet
Ce projet vise à **prédire les ventes** des différentes catégories de produits dans les magasins d'Équateur en utilisant des modèles de Machine Learning (XGBoost) et Deep Learning (LSTM).  
L'objectif est d'optimiser la gestion des stocks et d'améliorer la prise de décision commerciale.

---

##  Contenu du projet
- `final_modeles_previsions.ipynb` : Notebook principal contenant l'analyse, le preprocessing et la modélisation.
- `data/` : Dossier contenant les données utilisées pour l'entraînement et les tests.
- `requirements.txt` : Liste des bibliothèques nécessaires pour exécuter le projet.
- `README.md` : Ce fichier expliquant le projet.

---

## Installation et Prérequis

### 1️ Cloner le dépôt
```sh
git clone https://github.com/KADA-SEDODE/Pr-vision-des-ventes.git
cd Pr-vision-des-ventes

2️ Créer un environnement virtuel et installer les dépendances
python -m venv .venv
source .venv/bin/activate  # Sur Mac/Linux
.\.venv\Scripts\activate   # Sur Windows

pip install -r requirements.txt

3️ Lancer le notebook
jupyter notebook

 Modèles Utilisés
XGBoost : Principal algorithme utilisé pour la prévision.
LSTM (Long Short-Term Memory) : Testé pour capturer les tendances temporelles.
SHAP : Analyse d'interprétabilité des modèles.