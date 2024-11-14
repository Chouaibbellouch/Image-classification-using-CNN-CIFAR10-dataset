# Modèle CNN pour la classification d'images CIFAR-10

Ce répertoire contient un notebook Jupyter qui montre l'utilisation d'un réseau de neurones convolutif (CNN) pour classifier des images du jeu de données CIFAR-10. Le jeu de données CIFAR-10 est composé de 60 000 images en couleur réparties en 10 classes, y compris des avions, des voitures, des oiseaux, des chats, et plus encore. Le but de ce projet est de développer un modèle de deep learning capable d'identifier avec précision la bonne classe pour chaque image.

## Aperçu

Le notebook propose les éléments suivants :

- Chargement et visualisation du jeu de données CIFAR-10.
- Prétraitement des images pour une performance optimale du modèle.
- Construction d'un CNN en utilisant Keras.
- Compilation et entraînement du modèle.
- Évaluation des performances du modèle sur le jeu de test.
- Affichage des graphes de précision et de perte pour analyser l'entraînement.
- Prédictions sur des images non vues.

## Jeu de données

![CIFAR-10 Dataset](CIFAR-10%20dataset.png)

Le jeu de données CIFAR-10 contient :

- **Données d'entraînement** : 50 000 images (32x32 pixels chacune) avec 10 classes différentes.
- **Données de test** : 10 000 images avec les mêmes classes.

Les classes du CIFAR-10 sont :

0. Avion
1. Automobile
2. Oiseau
3. Chat
4. Cerf
5. Chien
6. Grenouille
7. Cheval
8. Bateau
9. Camion

## Architecture du modèle

Le réseau de neurones convolutif (CNN) est composé des éléments suivants :

- Plusieurs couches de convolution avec des fonctions d'activation ReLU pour l'extraction de caractéristiques.
- Couches de MaxPooling pour la réduction dimensionnelle.

Le modèle a été optimisé en utilisant l'optimiseur Adam avec l'entropie croissée catégorielle comme fonction de perte.

## Prérequis

Pour exécuter le notebook, vous aurez besoin de :

- Python 3.7+
- TensorFlow 2.0+
- NumPy
- Matplotlib
- Jupyter Notebook

Installez les dépendances en exécutant :

```sh
pip install tensorflow numpy matplotlib jupyter
```

## Pour commencer

1. Clonez ce répertoire sur votre machine locale :
   ```sh
   git clone <repository-url>
   ```
2. Naviguez vers le répertoire :
   ```sh
   cd <repository-directory>
   ```
3. Lancez Jupyter Notebook :
   ```sh
   jupyter notebook "CCN Model for Cifar10 Image Classification.ipynb"
   ```

Suivez les étapes dans le notebook pour charger le jeu de données CIFAR-10, construire et entraîner le modèle.

## Résultats

Le CNN est entraîné pendant plusieurs époques pour atteindre une haute précision. Les métriques d'évaluation telles que la précision et la perte sont tracées pour analyser les performances du modèle.

- **Précision d'entraînement** : Montre à quel point le modèle apprend sur les données d'entraînement.
- **Précision de validation** : Indique les performances du modèle sur des données non vues.

## Contribution

Si vous avez des questions concernant ce notebook, des améliorations ou des suggestions, vous pouvez m'envoyer un mail : chouaibconcours13\@gmail.com
