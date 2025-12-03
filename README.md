# 📊 Projet Big Data : Clustering K-Means avec PySpark et scikit-learn

Ce projet explore l'application de l'algorithme **K-Means** sur des jeux de données de différentes tailles (Small, Medium, Large) pour analyser la scalabilité et la performance de **PySpark** et **scikit-learn**.

Les notebooks ont été développés et exécutés sur **Google Colab**.

## 📂 Structure du Projet

Le code est réparti en 4 fichiers progressifs. Vous pouvez visualiser les résultats (graphiques, scores, clusters) directement en cliquant sur les fichiers ci-dessous :

### 1. `First try (small Data).ipynb`
* **Contenu :** Introduction et prise en main.
* **Données :** Wine Quality (Rouge/Blanc) (data downlaoded).
* **Code :** Configuration de l'environnement Spark et premier clustering simple.

### 2. `Two algorithms (small data) .ipynb`
* **Contenu :** Comparaison technique.
* **Données :** Wine Quality (Rouge/Blanc) (data imported by link).
* **Code :** Comparaison des performances entre **PySpark** et **Scikit-learn**. Analyse des métriques (Silhouette, Inertie, ARI) et visualisation PCA.

### 3. `Two algorithms (meduim data) .ipynb`
* **Contenu :** Gestion de données complexes.
* **Données :** Adult Dataset (Revenus).
* **Code :** Création d'un Pipeline ML complet pour traiter des variables mixtes (catégorielles et numériques) avant le clustering.

### 4. `Two algorithms (large data) .ipynb`
* **Contenu :** Big Data et cas réel.
* **Données :** Détection de fraude bancaire (Credit Card Fraud).
* **Code :** Gestion de gros volumes (Sampling, Caching), analyse de la pureté des clusters pour détecter la fraude et visualisation avancée.

## 🚀 Utilisation

Le projet est optimisé pour **Google Colab**.
Chaque notebook contient un bouton "Open in Colab" en haut de page (si visualisé sur GitHub) ou peut être importé directement dans Drive.

Les résultats des exécutions (scores de silhouette, graphiques Matplotlib/PCA) sont sauvegardés dans les notebooks pour une lecture immédiate sans ré-exécution nécessaire.

## 🛠️ Prérequis

* **Langage :** Python 3
* **Librairies principales :** PySpark, Pandas, Matplotlib, Scikit-learn.
