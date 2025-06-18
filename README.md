# Prediction-des-defauts-de-paiements
## Objectifs
- Construire un modèle prédictif fiable
- Identifier les facteurs les plus influents sur le risque de défaut
- Évaluer la performance du modèle via des métriques adaptées

## Méthodes utilisées
- Régression Logistique
- Analyse de la multicolinéarité (VIF)
- Sélection de variables
- Matrice de confusion, ROC, AUC

## Résultats
- Modèle final avec AUC = 0,72 
- Variables significatives : nombre de mois de retard, niveau d’éducation, statut marital
- Proposition d’un scoring client pour prédiction du risque

## Technologies
Python (Pandas, Scikit-Learn, Statsmodels, Seaborn)
Jupyter Notebook

## Fichiers clés
- `credit_card_default.ipynb` : Notebook Jupyter contenant l’analyse complète
- `rapport.pdf` : Rapport détaillé
- `graphes/` : Graphiques des performances du modèle

## Auteurs
Nelson Kokora
