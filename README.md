# Projet Python 
# A3 FISA S3E

## DESCRIPTION DU PROJET
Les incendies de forêt causés par le changement climatique représentent un grave problème 
environnemental et socio-économique. Le réchauffement de la planète et les modifications des 
schémas climatiques ont contribué à intensifier et à fréquenter ces incendies, mettant en danger les 
écosystèmes forestiers, la biodiversité et les communautés humaines.
Dans ce projet, nous souhaitons analyser des données satellites de feux en Turquie pendant une 
vingtaine d’années 2000-2021. Ces analyses vont aider des experts à mieux comprendre et maitriser 
ces incendies.

## ORGANISATION DU PROJET :
- 28 heures sont réservées pour le projet, réparties en 7 séances de 4h
  - 6 séances sont dédiées à la réalisation du projet.
    - Deux points de suivi avec intervenant sont à prévoir sur la deuxième et la cinquième séance.
  - La septième séance est réservée pour la soutenance.
- Le projet se déroule en groupe de 4 à 6 personnes.
- Le projet est à lancer pendant la dernière séance de TP.
  
## LIVRABLES DU PROJET :
- Un fichier Jupyter Notebook *.ipynb par groupe 
- Une soutenance présentant l’exploitation du jeu de données

## ATTENDUS DU PROJET :
- Import des données
- Analyse descriptive des données
  - Nettoyage des données 
  - Présentation des variables quantitatives
  - Présentation des variables qualitatives
  - Evolution des feux au fil des années
- Intelligence Artificielle
  - Compléter via de la classification la donnée manquante de la variable « Type »
  - Implémenter une fonctionnalité supplémentaire (au choix des étudiants)
    - Ex : Clustering spatial
    - Ex : Clustering temporel
    - Ex : Prédiction de l’évolution du type des feux
    - autre

## DONNEES DU PROJET :
- 21 fichiers *.csv (1 par an) ou 1 fichier "2000-2021 SINGLE TURKEY FIRE_MC61_214067.csv" de 17 Mb
- Feux en Turquie de 2000 à 2021
- Le jeu de données contient des données des feux de forets qui ont eu lieu en Turquie de 2000 à 2021. Il contient 211308 observations. Chaque observation contient les données de 15 facteurs :
  - ‘latitude and longitude’: Position géographique du feu.
  - ‘brightness’: Température de luminosité mesurée en kelvins
  - ‘scan and track’: Résolution spatiale
  - ‘acq_date’: Date de feu
  - ‘acq_time’: Heure d’acquisition du satellite (en UTC).
  - ‘satellite’: Detection par le satellite Terra ou le satellite Aqua
  - ‘instrument’: The MODIS instrument that tracks the observations is NASA’s Earth Observing System Terra and Aqua satellites. The orbit of the Terra satellite goes in the morning across the equator from north to south direction and Aqua passes in the same manner in the afternoon from south to north direction over the equator. This generates global coverage every 1 to 2 days. 
  - ‘confidence’: Indicateur de qualité
  - ‘version’: Traitement de la collecte et de la source des données
  - ‘bright_t31’: Température de luminosité mesurée en kelvins
  - ‘frp’: Puissance radiative du feu
  - ‘daynight’: D pour feu diurne, N pour feu nocturne
  - ‘type’: 0 pour un feu de végétation présumé, 1 pour un volcan actif, 2 pour d'autres sources terrestres statiques et 3 pour une détection en mer
 
  
