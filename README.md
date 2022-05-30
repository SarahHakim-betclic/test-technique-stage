# NBA predict MVP

## Predict MVP

Le trophée de NBA Most Valuable Player (MVP) est une récompense attribuée chaque année par la National Basketball Association (NBA) au meilleur joueur de la saison régulière.
Le but de ce projet est de prédire ce classement à partir des données collectées sur les joueurs et leurs équipes lors de la saison régulière. 

Le dataset est divisée en 2 parties. 
- train.csv : 1991-2020 NBA stats of players, teams and MVPs.
- test.csv : 2021 NBA stats of players and teams.

Certains joueurs peuvent apparaitre plusieurs fois s'ils ont changé d'équipe en cours d'année. 

## Questions 

1 - Construire un modèle de machine learning à partir des données de train afin prédire le pourcentage des votes du jury reçu par un joueur. 
La variable à prédire est le **share**.

2 - Utiliser les prédictions du modèle pour reconstituer le classement MVP dans le dataset de test. 
Ajouter une colonne "rank", qui contiendrait le classement des joueurs sur la saison 2021. 

3 - Calculer le NDGC (Normalized Discounted Cumulative Gain) sur le dataset de test. 
Cette métrique permet d'évaluer la qualité du classement.

## Rendu final

Le rendu final : 
- un document pdf (explication de la méthode utilsée, analyse des données, évaluation du modèle de machine learning, résultats obtenus, graphes...) 
- un jupyter notebook contenant le code (utilisation de pandas, scikit-learn, plots)
- un csv de prédictions pour la saison 2021 à partir des données de test avec :  mom du joueur, share prédit, rang prédit.

## Liens utiles

- https://github.com/fabianp/mash_2016_sklearn_intro
- https://github.com/jakevdp/sklearn_tutorial
- https://scikit-learn.org/stable/modules/generated/sklearn.metrics.ndcg_score.html 
- https://en.wikipedia.org/wiki/Discounted_cumulative_gain#Normalized_DCG

## Glossaire

Glossaire : https://www.basketball-reference.com/about/glossary.html

## Sources
Voting data : https://www.basketball-reference.com/awards/awards_2016.html  
Player data : https://www.basketball-reference.com/leagues/NBA_2022.html  
Teams data : https://www.basketball-reference.com/leagues/NBA_2021_standings.html  

Dataset : https://www.kaggle.com/datasets/vivovinco/19912021-nba-stats
