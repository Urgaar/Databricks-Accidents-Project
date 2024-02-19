# Databricks-Accidents-Project

Ce projet consiste à faire un modèle de prédiction de la gravité des accidents en fonction de différentes variables.
Pour mener à bien ce projet on utilise différents classifieurs:
- KNN
- Random Forest
- Decisiontree
## Sources du projet :
Le projet et les données s'inspirent de ce tutoriel d'Ilyes Talbi :
https://larevueia.fr/xgboost-vs-random-forest-predire-la-gravite-dun-accident-de-la-route/

## Contenu du repo :
Ce repo contient 2 exports notebook en dbc:
- Modélisation qui contient toutes les étapes nécéssaires à la classification
- Test API qui contient le test de fonctionnement de l'API en python

## Lien du endpoint:
url= https://adb-7179589947499295.15.azuredatabricks.net/serving-endpoints/random_forest/invocations
