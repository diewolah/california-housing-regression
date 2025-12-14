# California Housing Regression Project

## Description
Ce projet consiste à prédire la **valeur médiane des maisons en Californie** (`median_house_value`) à partir de différentes caractéristiques du logement et de la population.  
Il illustre l'utilisation de la **régression linéaire**, des **tests d’hypothèses** et de l'**analyse des résidus** pour construire un modèle statistique interprétable.

Le dataset contient des variables quantitatives (ex: `median_income`, `total_rooms`) et qualitatives (ex: `ocean_proximity`).


---

## Technologies

- **Langage :** R  
- **Packages :** tidyverse, corrplot  
- **Outils :** RStudio 

---

## Étapes du projet

1. **Import et exploration des données**  
   - Affichage des premières lignes, structure et résumé du dataset.  
   - Vérification des valeurs manquantes (`total_bedrooms` contient 207 valeurs manquantes).  

2. **Analyse exploratoire des données (EDA)**  
   - Histogrammes des variables clés.  
   - Nuages de points pour visualiser les relations (ex: `median_income` vs `median_house_value`).  
   - Matrice de corrélation pour identifier les variables les plus influentes.  

3. **Modélisation**  
   - Construction d’un modèle de **régression linéaire multiple**.  
   - Interprétation des coefficients et significativité (`p-values`).  

4. **Tests d’hypothèses**  
   - H₀ : Le revenu médian n’influence pas le prix des maisons.  
   - H₁ : Le revenu médian influence le prix des maisons.  

5. **Analyse des résidus**  
   - Vérification de la linéarité et normalité des résidus.  

6. **Conclusion**  
   - Le revenu médian et les caractéristiques des logements sont les variables les plus discriminantes.  
   - Le modèle est globalement significatif et respecte les hypothèses principales.

---

## Résultats clés

- **R² multiple :** 0.6465 (~65% de la variance expliquée)  
- **Variables les plus importantes :** `median_income`, `total_rooms`, `households`, `population`  
- **Variables avec valeurs manquantes** : ``total_bedrooms``. Le modèle de régression linéaire (`lm()`) a automatiquement ignoré ces 207 observations lors de l'ajustement.

---

## Date
13/10/2025

## Auteur
Diewo Lah

