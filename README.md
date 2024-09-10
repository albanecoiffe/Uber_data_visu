# Visualisation des Données Uber avec Streamlit   

[Streamlit page](https://uberdatavisuappwithpython.streamlit.app/)    
Ce projet utilise Streamlit pour créer un tableau de bord interactif permettant d'explorer les données des trajets Uber de janvier 2015 à New York. Le but est de proposer des visualisations dynamiques et des analyses des différents aspects de ces données, telles que le nombre de passagers, les pourboires, les distances, et bien plus encore.

## 📊 Fonctionnalités Principales
- Visualisation des données par heure : Nombre de passagers, nombre de trajets, pourboires et distances par heure sous forme de graphiques en ligne et en barres.
- Statistiques à des heures spécifiques : Statistiques détaillées à 22h et 4h : distance totale, nombre de passagers, pourboires, et nombre de trajets.
- Distribution du montant des courses selon la distance : Distribution des tarifs moyens par rapport à la distance du trajet sous forme de graphiques.
- Analyse des montants moyens : Moyennes des montants des courses, des pourboires et du montant total par heure.
- Vitesse moyenne des trajets : Visualisation de la vitesse moyenne des trajets par heure.
- Cartes des trajets : Carte interactive des points de départ et d'arrivée des trajets avec deux vues : simple carte et carte 3D avec pydeck.  

## 🛠️ Technologies Utilisées
- `Python` : Langage de programmation principal.
- `Streamlit` : Framework utilisé pour créer le tableau de bord interactif.
- `Pandas` : Pour la manipulation des données.
- `Altair et Seaborn` : Bibliothèques pour la visualisation des données.
- `Pydeck` : Pour créer des visualisations géospatiales interactives.
- `Matplotlib` : Utilisé pour certaines visualisations supplémentaires.
