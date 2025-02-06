Ce projet a pour objectif de prédire la gravité des accidents de la route à partir de différentes caractéristiques

Sources des Données
Les données utilisées dans ce projet proviennent de data.gouv.fr, le portail de données ouvertes de la France. Le projet utilise quatre fichiers CSV :

carac.csv - Contient des informations sur les accidents.
lieux.csv - Fournit des détails sur les lieux des accidents.
veh.csv - Données relatives aux véhicules impliqués dans les accidents.
vict.csv - Informations sur les victimes des accidents.

Ce repository contient le notebook contenant le code avec le traitement des données et l'entrainement des classifieurs.
On test les classifieurs des K plus proche voisins, l'abre de décision et la foret Aléatoire avec leurs meilleurs paramètres.
Celui qui a été retenu est l'Abre de décision avec un F1 score 0.431 et un accuracy score à 0.610
