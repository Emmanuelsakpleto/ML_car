# Prédiction du Prix des Voitures

## Description

Ce projet a pour but de prédire le prix des voitures en utilisant des techniques d'apprentissage automatique. Il inclut l'exploration des données, le prétraitement, l'ingénierie des caractéristiques et l'entraînement de différents modèles de régression.

## Installation

Pour exécuter ce projet, vous devez installer les bibliothèques Python suivantes :

  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`

Vous pouvez les installer via pip :

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Utilisation

1.  **Téléchargez le jeu de données** : Le fichier `CarPrice_Assignment.csv` est nécessaire pour ce projet. Vous pouvez le trouver sur Kaggle.

2.  **Ouvrez le notebook Jupyter** : Exécutez toutes les cellules du fichier `Car_ML.ipynb` dans un environnement Jupyter Notebook.

    ```bash
    jupyter notebook Car_ML.ipynb
    ```

## Fichiers Principaux

  - `Car_ML.ipynb`: Le notebook Jupyter contenant tout le code d'analyse et de modélisation.
  - `CarPrice_Assignment.csv`: Le jeu de données des prix de voitures utilisé.

## Modèles Utilisés

Les modèles de régression suivants ont été utilisés et évalués :

  - Régression Linéaire
  - Arbre de Décision (Decision Tree Regressor)
  - Forêt Aléatoire (Random Forest Regressor)

## Conclusion

La régression linéaire s'est avérée inappropriée pour ce jeu de données (avec un R² négatif), ce qui suggère que les relations sont non-linéaires. Il est recommandé d'utiliser des modèles non-linéaires comme les Arbres de Décision ou les Forêts Aléatoires pour une meilleure performance.