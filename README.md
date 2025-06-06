# Formation CNRS - Introduction au machine learning et au deep learning avec Python

## Description de la formation du 11 au 13 juin 2025

Cette [formation](https://cnrsformation.cnrs.fr/introduction-machine-learning-deep-learning-avec-python?axe=160) sera encadrée par:

- Tabea Rebafka
- Daphné Giorgi
- Vincent Lemaire 

Les cours se dérouleront 

- de **9h00 à 17h30** du mercredi 11 au vendredi 13 juin 2025
- en **salle 113, couloir 16-26**, au 4, place Jussieu, 75005
- avec une session théorique le matin et des travaux pratiques l'après midi.


| Horaire     | Sujet             | Salle     |
| ----------- | ----------------- | --------- |
| 8:30-9:00   | Accueil café      | 16-26 113 |
| 9:00-12:00  | Théorie           | 16-26 113 |
| 12:00-13:00 | Pause déjeuner    | --------- |
| 13:00-17:00 | Pratique          | 16-26 113 |

Les objectifs de la formation sont
- Comprendre les concepts mathématiques des méthodes de l'apprentissage statistique supervisé (régression et classification)
- Connaître les principaux algorithmes du deep learning
- Savoir utiliser les librairies Python pour la mise en œuvre des méthodes de machine learning et de deep learning
- Savoir choisir les algorithmes adaptés aux cas d'usages
- Savoir interpréter les résultats des algorithmes et identifier leurs limites

## Prérequis

Il est demandé aux participants d'être équipés d'un ordinateur portable et il est fortement recommandé d'installer en avance les logiciels et outils nécessaires à la formation.

Une version de python supérieure à 3.12 est requise, pour vérifier votre version : 

> python3 --version

L'idéal est de créer un environement virtuel, pour éviter tout conflit avec d'autres installations de paquets.

> cd TPs

> python3 -m venv .venv

> source .venv/bin/activate 

Les paquets Python nécessaires à la formation sont listés dans le fichier `requirements.txt`. Pour les installer depuis la console, il suffit de taper la commande :

> pip install -r requirements.txt

Les travaux pratiques se feront sur des notebook Python. Pour vérifier que les dépendances ont été correctement installées, lancer un `jupyterlab` depuis le répertoire `TPs` en tapant la commande

> jupyter lab

et exécuter le notebook `test.ipynb`.

## Matériel

Les transparents des cours du matin se trouvent dans le répertoire `Cours`.

Les notebook pour les travaux pratiques se trouvent dans le répertoire `TPs`.

Les fichiers de données du 2ème jour sont à télécharger [ici](https://sdrive.cnrs.fr/s/qHM5HDAGr6w8J4n) et à copier dans le répertoire `TPs/data`. 
