# NLTK
# Analyseur de Sentiment en Python

Ce projet est un analyseur de sentiment en Python qui classe les commentaires en ligne comme étant positifs ou négatifs en fonction de leur contenu textuel.
Il utilise des techniques de traitement automatique du langage naturel (TALN) et un modèle de régression logistique pour effectuer cette classification.

## Fonctionnalités

- Classification des commentaires en positifs ou négatifs.
- Entraînement du modèle sur un jeu de données d'entraînement.
- Utilisation d'une représentation TF-IDF pour la vectorisation du texte.
- Prétraitement des données textuelles avec NLTK (tokenization, lemmatisation).
- Possibilité d'ajouter des mots positifs et négatifs personnalisés.

## Prérequis

Ce projet nécessite Python 3.x et les bibliothèques Python suivantes :
- nltk
- scikit-learn
- datasets

Vous pouvez installer ces bibliothèques en utilisant `pip` :

```bash
pip install nltk scikit-learn datasets
