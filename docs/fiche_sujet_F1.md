
# Fiche du sujet F1 : Risque de crédit en Allemagne

## 1. Présentation du sujet

Le projet porte sur la prédiction du risque de crédit en Allemagne à partir du jeu de données German Credit.

L'objectif est d'utiliser des techniques de Machine Learning pour identifier les demandeurs présentant un bon ou un mauvais profil de risque.

## 2. Problématique

Comment prédire le risque de crédit d'un demandeur à partir de ses caractéristiques personnelles, financières et de son historique de crédit ?

## 3. Objectif du projet

Développer un modèle de classification binaire capable de distinguer les bons risques des mauvais risques.

Une attention particulière est accordée à la détection des mauvais risques, car les erreurs de classification peuvent entraîner des pertes financières.

## 4. Jeu de données

Nom : Statlog German Credit Data.

Source : UCI Machine Learning Repository.

Lien :
https://archive.ics.uci.edu/dataset/144/statlog+german+credit+data

Nombre d'observations : 1 000.

Nombre de variables explicatives : 20.

Variable cible : Risk.

Les deux classes sont :
- 1 : Bon risque.
- 2 : Mauvais risque.

## 5. Algorithme principal

Random Forest Classifier.

Cet algorithme repose sur la combinaison de plusieurs arbres de décision afin d'améliorer la qualité des prédictions.

## 6. Préparation des données

- Identification des variables numériques et catégorielles.
- Encodage des variables catégorielles avec OneHotEncoder.
- Séparation des données en apprentissage et test.
- Utilisation d'un Pipeline pour intégrer le prétraitement et le modèle.

## 7. Évaluation

Les métriques utilisées sont :

- Accuracy.
- Precision.
- Recall.
- F1-score.
- Matrice de confusion.

La validation croisée stratifiée est utilisée pour le réglage des hyperparamètres.

## 8. Particularité du sujet

Les erreurs de classification n'ont pas le même coût financier.

Le projet étudie donc également le choix du seuil de décision afin de mieux prendre en compte le risque financier.

## 9. Résultat attendu

Obtenir un modèle capable d'identifier les mauvais risques de crédit et de fournir une aide à la décision aux établissements financiers.
