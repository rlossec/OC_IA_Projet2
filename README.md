# EDA du dataset des arbres de Paris

Bienvenue dans le projet d'exploration et de nettoyage du dataset d'arbres en vue d'une étude des tournées d'arrosage. Ce README fournit des informations importantes sur les données, le processus de nettoyage et les étapes d'exploration que nous avons entreprises.

## Aperçu du Dataset
[Dataset](https://opendata.paris.fr/explore/dataset/les-arbres/export/)
Le dataset que nous utilisons pour cette étude contient des informations sur les arbres, notamment leur localisation, leur circonférence, leur hauteur, et leur stade de développement.

## Objectif de l'étude

L'objectif principal de cette analyse est de comprendre les caractéristiques des arbres en relation avec les tournées d'arrosage. Nous explorerons la distribution des arbres, identifierons les valeurs aberrantes, traiterons les valeurs manquantes, et préparerons les données pour une analyse approfondie.

## Étapes de nettoyage et d'exploration

1. **Suppression des lignes aberrantes :**
   - Nous avons identifié et supprimé les lignes qui contiennent des valeurs aberrantes, telles que des circonférences ou hauteurs extrêmement grandes.

2. **Traitement des valeurs manquantes :**
   - Les valeurs manquantes dans les colonnes "circonference_cm", "hauteur_m", et "stade_developpement" ont été traitées de manière appropriée. Les choix spécifiques de traitement peuvent être consultés dans le code source.

3. **Exploration des tournées d'arrosage :**
   - Nous explorerons la distribution des arbres en fonction de leur localisation, de leur stade de développement, de leur circonférence et de leur hauteur pour obtenir des informations pertinentes sur les tournées d'arrosage.

## Comment utiliser ce Dataset

Le fichier principal du dataset est `p2-arbres-fr.csv`. Le code source utilisé pour l'exploration et le nettoyage est disponible dans le fichier Jupyter Notebook `script.ipynb`. Vous pouvez exécuter ce notebook pour reproduire les étapes que nous avons suivies.


Bonne exploration !


# EDA of the Paris Trees Dataset

Welcome to the exploration and cleaning project of the tree dataset for a study on watering routes. This README provides important information about the data, the cleaning process, and the exploration steps we have taken.

## Dataset Overview
[Dataset](https://opendata.paris.fr/explore/dataset/les-arbres/export/)
The dataset we use for this study contains information about trees, including their location, circumference, height, and development stage.

## Study Objective

The main objective of this analysis is to understand the characteristics of trees in relation to watering routes. We will explore the distribution of trees, identify outliers, handle missing values, and prepare the data for in-depth analysis.

## Cleaning and Exploration Steps

1. **Removal of Outlying Rows:**
   - We identified and removed rows that contain outliers, such as extremely large circumferences or heights.

2. **Handling Missing Values:**
   - Missing values in the columns "circonference_cm," "hauteur_m," and "stade_developpement" have been appropriately handled. Specific choices for treatment can be found in the source code.

3. **Exploration of Watering Routes:**
   - We will explore the distribution of trees based on their location, development stage, circumference, and height to gather relevant information about watering routes.

## How to Use this Dataset

The main file of the dataset is `p2-arbres-fr.csv`. The source code used for exploration and cleaning is available in the Jupyter Notebook file `script.ipynb`. You can run this notebook to replicate the steps we have taken.

Happy exploring!
