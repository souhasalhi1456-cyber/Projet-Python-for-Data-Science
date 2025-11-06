# Health Data Analysis & Prediction Project

## Description du Projet
Ce projet s'inscrit dans le cadre de la mise en place d'un système décisionnel qui intègre des analyses de données et des prévisions basées sur des modèles de machine learning. L'objectif est de fournir des outils d'aide à la décision pour améliorer la compréhension des facteurs influençant la santé des individus.

### Problématique
Comment peut-on prédire efficacement l'état de santé global d'un individu à partir de ses habitudes de vie telles que l'alimentation, le sommeil, l'activité physique, la consommation d'alcool et le tabagisme ?

## Données
- **Source** : Kaggle - Health and Lifestyle Data for Regression
- **Taille** : 1000 observations
- **Format** : CSV (`synthetic_health_data.csv`)

### Structure des Données
- **Âge** : Âge de l'individu en années (variable continue)
- **IMC** : Indice de Masse Corporelle (variable continue)
- **Fréquence_Exercice** : Nombre de jours d'exercice par semaine (catégorique, 0-7)
- **Qualité_Régime** : Indice de qualité alimentaire (continue, 0-100)
- **Heures_Sommeil** : Nombre moyen d'heures de sommeil par nuit (continue)
- **Statut_Fumeur** : Variable binaire (0 = Non-fumeur, 1 = Fumeur)
- **Consommation_Alcool** : Unités d'alcool consommées par semaine (continue)
- **Score_Santé** : Score de santé global (continue, 0-100)

## 📁 Structure du Projet
Projet-Python-for-Data-Science/
│
├── 📄 README.md
├── 📊 CAHIER DES CHARGES Poo.pdf
├── 🐍 projet poo version finale.ipynb
├── 📈 synthetic_health_data.csv


## Étapes du Projet
1. **Exploration et nettoyage des données** ✓
2. **Normalisation et réduction de dimensionnalité**
3. **Conception du data warehouse (schéma en étoile)**
4. **Alimentation avec Talend**
5. **Visualisation interactive via Power BI**
6. **Modélisation (régression linéaire + RFE + Cross-Validation)**

## Méthodologie Machine Learning
- **Régression Linéaire** pour la prédiction du score de santé
- **RFE (Recursive Feature Elimination)** pour la sélection de features
- **Cross-Validation** pour l'évaluation des modèles
- **Analyse exploratoire** avec visualisations



## Auteurs
- **Encadré par** : Dr. Eva JEBALI
- **Réalisé par** : Souha Salhi

