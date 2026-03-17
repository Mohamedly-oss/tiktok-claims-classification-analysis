# tiktok-claims-classification-analysis
Analyse statistique et modélisation prédictive pour la classification des revendications sur TikTok.

# 📱 TikTok Claims Classification - Data Science Project


## 📌 Présentation du Projet
Ce projet a pour objectif est d'aider les équipes de modération de TikTok à automatiser la distinction entre les **"claims"** (affirmations) et les **"opinions"**.

L'enjeu est de taille : les comptes vérifiés ayant tendance à publier davantage d'opinions, comprendre leur comportement permet d'optimiser le filtrage des contenus signalés.

---

## 📊 Objectifs et Analyse
* **Analyse Statistique :** Vérifier les corrélations entre les métriques de performance des vidéos (vues, partages, likes) et le type de contenu.
* **Tests d'Hypothèses :** Application de statistiques descriptives et inférentielles pour valider les tendances observées.
* **Modélisation :** Prédire le `verified_status` (statut de vérification) à l'aide d'une **régression logistique**.

---

## 🛠️ Méthodologie
1.  **Exploration (EDA) :** Nettoyage des données et gestion de la multicolinéarité (exclusion de `video_like_count`).
2.  **Ingénierie des caractéristiques :** Encodage des variables catégorielles.
3.  **Modélisation :** Entraînement d'un modèle de régression logistique avec `Scikit-learn`.
4.  **Évaluation :** Analyse via la matrice de confusion et les scores de classification.

---

## 📈 Résultats Clés
Le modèle de régression logistique a montré une capacité prédictive satisfaisante :

| Métrique | Score |
| :--- | :--- |
| **Précision (Precision)** | 69% |
| **Rappel (Recall)** | 66% |
| **Score F1** | 66% |

> **Insight Majeur :** La **durée de la vidéo** est le facteur le plus influent. Chaque seconde supplémentaire augmente de façon significative la probabilité que le compte soit vérifié.

---

## 📂 Structure des fichiers
* `Projet_TIK_Tok_prediction.ipynb` : Analyse complète et code Python.
* `TikTok_executive_summary.pdf` : Rapport de synthèse destiné aux décideurs.

---

## 👤 Auteur
**Mohamed Ly** *Doctorant en Économie à l'UCAD | Spécialiste Data Science & Analyse Agricole* [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/)

