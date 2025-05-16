# 📊 Most Popular Programming Languages – Shiny App

Cette application interactive développée avec **Shiny** permet de visualiser l'évolution de la popularité des langages de programmation au fil du temps à partir d'un jeu de données. L'utilisateur peut explorer les tendances, comparer plusieurs langages, et analyser leur popularité moyenne sur une période définie.

## Fonctionnalités

- **Sélection de langages** : Choisissez un ou plusieurs langages de programmation à visualiser.
- **Filtrage temporel** : Définissez une plage de dates pour explorer les tendances sur une période donnée.
- **Graphiques dynamiques** :
  - 📈 **Popularité dans le temps** : Évolution de la popularité par langage.
  - 📊 **Popularité moyenne** : Comparaison de la moyenne sur la période.

## 📁 Données

Les données sont chargées depuis `ProgrammingLanguages.csv` et analysées à l'aide de `tidyverse` et `lubridate`.

## Technologies utilisées

- **R / Shiny**
- **dplyr**, **tidyr**, **lubridate**
- **ggplot2** + **plotly** pour les graphiques interactifs

## ▶️ Lancer l'application

```r
shiny::runApp()
