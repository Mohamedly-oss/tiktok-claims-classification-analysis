# tiktok-claims-classification-analysis
Analyse statistique et modélisation prédictive pour la classification des revendications sur TikTok.

TikTok Claims Classification - Analyse Statistique et Régression Logistique
📌 Présentation du Projet
Ce projet a été réalisé dans le cadre de la certification Google Advanced Data Analytics. L'objectif principal est d'aider les équipes de modération de TikTok à mieux comprendre et classifier les contenus des utilisateurs.

L'analyse se concentre sur la distinction entre les "claims" (affirmations) et les "opinions", tout en cherchant à prédire le statut de vérification des comptes (vérifié vs non-vérifié) en fonction des caractéristiques des vidéos.

📊 Objectifs Business
Automatisation : Faciliter le tri des vidéos pour les modérateurs humains.

Analyse Comportementale : Identifier si les comptes vérifiés ont des habitudes de publication différentes des comptes non-vérifiés.

Prédiction : Développer un modèle de régression logistique pour prédire le statut verified_status.

🛠️ Technologies Utilisées
Langage : Python

Librairies : * Pandas & NumPy (Manipulation des données)

Matplotlib & Seaborn (Visualisation)

Scipy (Tests d'hypothèses statistiques)

Scikit-learn (Machine Learning - Régression Logistique)

📈 Méthodologie et Étapes
Exploration des données (EDA) : Analyse des distributions, des valeurs manquantes et des corrélations.

Tests d'Hypothèses : Réalisation de tests statistiques pour valider les relations entre le type de contenu et le statut du compte.

Prétraitement : Encodage des variables catégorielles et gestion de la multicolinéarité (exclusion de variables trop corrélées comme video_like_count).

Modélisation : Construction et entraînement d'un modèle de régression logistique.

Évaluation : Utilisation de la matrice de confusion et des scores de précision/rappel.

🚀 Résultats Clés
Performance du modèle :

Précision : 61% à 69% (selon les itérations).

Rappel (Recall) : 84% (très efficace pour identifier les classes positives).

Score F1 : 66%.

Insight majeur : La durée de la vidéo est un prédicteur significatif. Plus une vidéo est longue, plus la probabilité que le compte soit vérifié augmente. Les autres caractéristiques (vues, partages) présentent une association beaucoup plus faible.

📂 Structure du Repository
Projet_TIK_Tok_prediction.ipynb : Notebook Jupyter contenant l'intégralité du code et de l'analyse.

TikTok_executive_summary.pdf : Résumé synthétique des résultats destiné aux parties prenantes.

data/ : (Optionnel) Dossier contenant le dataset utilisé.

Auteur : Mohamed Ly

Doctorant en Économie | Passionné par la Data Science
