# Notebooks Kotlin

Collection de notebooks Jupyter pour l'apprentissage et la documentation du langage Kotlin.

## Description

Ce projet regroupe des notebooks interactifs permettant d'explorer et de documenter les différentes fonctionnalités du langage Kotlin. Chaque notebook présente des concepts spécifiques avec des exemples de code exécutables et des explications détaillées.

## Notebooks disponibles

### `generiques-obj-ext.ipynb`

Ce notebook couvre les concepts suivants :

- **Génériques** : Utilisation des types paramétrés pour créer des classes réutilisables
  - Exemple : classe `Question<T>` avec différents types (String, Boolean, Int)

- **Objets singleton** : Déclaration d'objets uniques avec le mot-clé `object`
  - Exemple : `StudentProgress` pour suivre la progression

- **Objets compagnons** : Utilisation de `companion object` pour des membres accessibles via le nom de la classe
  - Exemple : accès à `Quiz.answered` et `Quiz.total`

## Prérequis

Pour utiliser ces notebooks, vous aurez besoin de :

- Jupyter Notebook ou JupyterLab
- Un kernel Kotlin pour Jupyter (par exemple, [Kotlin Jupyter Kernel](https://github.com/Kotlin/kotlin-jupyter))

## Installation du kernel Kotlin

Pour installer le kernel Kotlin pour Jupyter :

```bash
pip install kotlin-jupyter-kernel
```

Ou suivez les instructions sur le [dépôt officiel](https://github.com/Kotlin/kotlin-jupyter).

## Utilisation

1. Clonez ce dépôt
2. Lancez Jupyter Notebook ou JupyterLab
3. Ouvrez le notebook souhaité
4. Exécutez les cellules séquentiellement pour voir les exemples en action

```bash
jupyter notebook
```

## Contribuer

N'hésitez pas à ajouter de nouveaux notebooks couvrant d'autres aspects du langage Kotlin.

## Licence

Ce projet est destiné à l'apprentissage et à la documentation.