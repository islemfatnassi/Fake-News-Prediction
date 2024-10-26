# Fake News Prediction Project

## Description
Ce projet utilise le Machine Learning et le Traitement du Langage Naturel (NLP) pour prédire si un article de presse est une fausse nouvelle ou une information véridique. En s’appuyant sur des techniques de classification, ce modèle vise à automatiser la détection de fake news en analysant les textes des articles.

## Table des Matières
1. [Contexte du Projet](#contexte-du-projet)
2. [Dataset](#dataset)
3. [Prérequis](#prérequis)
4. [Installation](#installation)
5. [Structure du Projet](#structure-du-projet)
6. [Usage](#usage)
7. [Résultats](#résultats)
8. [Améliorations Futures](#améliorations-futures)
9. [Contributeurs](#contributeurs)
10. [Licence](#licence)

## Contexte du Projet
La propagation de fausses informations sur internet est un problème majeur, notamment avec l'influence des médias sociaux et des plateformes en ligne. Ce projet propose une solution pour détecter automatiquement les fausses nouvelles à l’aide d'algorithmes de machine learning et de NLP, contribuant ainsi à une meilleure vérification des informations.

## Dataset
Le dataset utilisé dans ce projet est issu de [Kaggle](https://www.kaggle.com/) et contient les informations suivantes :
- `id` : Identifiant unique pour chaque article.
- `title` : Titre de l'article.
- `author` : Auteur de l'article.
- `text` : Texte de l'article, parfois incomplet.
- `label` : 1 pour Fake News et 0 pour Real News.

## Prérequis
Les bibliothèques et outils suivants sont nécessaires pour exécuter le projet :
- Python 3.x
- Jupyter Notebook (optionnel pour l'exploration)
- Pandas
- NumPy
- Scikit-Learn
- NLTK
- Matplotlib
- Seaborn

## Installation
1. **Clonez le dépôt** :
   ```bash
   git clone https://github.com/votre_nom_d_utilisateur/FakeNewsPrediction.git
   cd FakeNewsPrediction

