# sign-language-detection
Ce projet consiste à créer un programme capable de reconnaître et d'interpréter les gestes de la langue des signes américaine (LSA) à partir d'images fixes. L'objectif est de classifier correctement les images de signes afin de créer un outil utile pour les personnes sourdes ou malentendantes qui souhaitent communiquer avec des personnes ne comprenant pas la LSA, ainsi que pour les contextes éducatifs ou de formation.

## L'ensemble de données
Nous avons collecté un ensemble de données d'images de signes de la LSA à partir de cette source:
[Dataset](https://www.kaggle.com/datasets/datamunge/sign-language-mnist?select=sign_mnist_test)

## Préparation de données
Nous avons nettoyé et préparé les données en redimensionnant les images à une taille uniforme, en normalisant les pixels et en les divisant en ensembles de formation, de validation et de test pour l'entraînement et l'évaluation de notre modèle.

## Modèle de classification
Nous avons utilisé un réseau de neurones convolutif (CNN) pour créer notre modèle de classification d'images. Nous avons entraîné le modèle sur les données d'entraînement et avons utilisé les données de validation pour optimiser les paramètres du modèle et éviter le surapprentissage. Nous avons finalement évalué les performances du modèle sur l'ensemble de données de test.

## Contributeur
- [Chentoui Abdelali](https://github.com/AbdelaliChe)
