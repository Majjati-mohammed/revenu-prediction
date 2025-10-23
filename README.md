#  Revenu Prediction using Linear Regression

##  Description
Ce projet a pour objectif de prédire le **revenu des employés** à partir de plusieurs variables explicatives telles que :
- l’âge,
- l’expérience professionnelle,
- le nombre d’heures travaillées par semaine,
- et d’autres caractéristiques.

Le modèle utilisé est une **régression linéaire (Linear Regression)**, développée à l’aide de la bibliothèque **scikit-learn**.

---

##  Technologies utilisées
- **Python 3.x**
- **pandas** — manipulation et nettoyage des données  
- **numpy** — calculs numériques  
- **matplotlib / seaborn** — visualisation  
- **scikit-learn** — modélisation (LinearRegression)

---

##  Étapes du projet
1. **Chargement des données**
   - Fichier JSON : `employes_data.json`
2. **Nettoyage**
   - Traitement des valeurs manquantes  
   - Conversion des types de variables
3. **Exploration**
   - Statistiques descriptives  
   - Visualisations (heatmap, pairplot)
4. **Modélisation**
   - Séparation en jeu d’entraînement et de test  
   - Entraînement du modèle de régression linéaire  
5. **Évaluation**
   - MSE (Mean Squared Error)  
   - R² Score  
6. **Analyse des résultats**
   - Interprétation du coefficient directeur et de l’interception  
   - Visualisation des prédictions

---

##  Résultats attendus
- Compréhension de la relation entre les variables (âge, expérience, heures/semaine) et le revenu.
- Capacité de prédire le revenu d’un employé selon ses caractéristiques.

