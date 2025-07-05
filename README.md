# 🕵️‍♀️ Analyse de Fraude sur Cartes de Crédit

Ce projet explore la détection de transactions frauduleuses à l’aide de techniques d’apprentissage automatique (SVM) et d’analyse statistique. Il combine **Python** (machine learning) et **R** (visualisation et prétraitement) sur un jeu de données déséquilibré.

## 🔍 Objectifs

- Appliquer un **classificateur SVM** pour identifier les fraudes.
- Gérer le **déséquilibre des classes**, un problème courant dans les données de fraude.
- Visualiser les performances du modèle avec des métriques adaptées (précision, rappel, matrice de confusion, etc.).
- Présenter une approche comparative entre Python et R.

## 📁 Contenu du projet

| Fichier | Description |
|--------|-------------|
| `creditcard_fraud.ipynb` | Analyse Python avec SVM et gestion de l’échantillonnage |
| `creditcard.Rmd`         | Rapport RMarkdown avec visualisation et modélisation |
| `creditcard.html`        | Version HTML rendue du fichier `.Rmd` |

## ⚙️ Technologies utilisées

- **Python** : `pandas`, `scikit-learn`, `matplotlib`, `seaborn`
- **R** : `tidyverse`, `e1071`, `caret`, `ggplot2`
- Outils : Jupyter Notebook, RMarkdown, Git

## 📌 Remarques

- Le dataset est **fortement déséquilibré** (très peu de fraudes). Des techniques comme le sous-échantillonnage ou SMOTE sont considérées.
- Le projet vise également à illustrer comment **intégrer Python et R dans une même démarche d’analyse**.

## 👤 Auteur

- **Aymane Mimoun**

---

