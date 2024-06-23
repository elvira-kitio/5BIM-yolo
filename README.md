# Détection d'Ordinateurs et de Souris avec OpenCV et YOLO

Ce projet utilise OpenCV et le modèle de détection d'objets YOLO pour détecter des ordinateurs et des souris dans des images ou des flux vidéo.

## Prérequis

- Python 3.6 ou supérieur
- Les dépendances listées dans `requirements.txt`

## Installation

1. Clonez le dépôt GitHub :
   ```bash
   git clone https://github.com/5BIM-yolo.git
   cd 5BIM-yolo
Installez les dépendances 
pip install -r requirements.txt

Exécution du Projet
Pour détecter dans un flux vidéo ou une image
Assurez-vous que vous avez les fichiers de configuration YOLO (yolov3.cfg), les poids du modèle (yolov3.weights) et le fichier des noms des classes (coco.names).

Exécutez le script yolo.py :
python yolo.py

Description des Fichiers
yolo.py : Le script principal qui charge le modèle YOLO, détecte les objets et affiche les résultats.
requirements.txt : Liste des dépendances nécessaires pour exécuter le projet.
README.md : Ce fichier avec des instructions sur l'installation et l'exécution du projet.
Structure du Code
Le code est organisé en classes pour suivre une approche de programmation orientée objet (POO) :

ImageLoader : Gère le chargement des images ou des vidéos.
YoloDetector : Utilise le modèle YOLO pour détecter les objets.
DetectionSystem : Intègre ImageLoader et YoloDetector pour le traitement complet de l'image ou du flux vidéo.

Contributeurs
Elvira KITIO DJOUAKA 

