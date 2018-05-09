# Contexte

L'avancée technologique nous permet aujourd'hui de modéliser à travers des détecteurs la position d'un appareil mobile (e.g. persone, avion, voiture etc).
La récolte de ses données nous permet certes d'avoir une vision globable de sa trajectoire, mais il arrive qu'il y ait des erreurs de détection.

En notre possession se trouve un jeu de données de la forme suivante :

```
#Trajectory	Time	X	Y	Z
1	00:00:00	-402	-131	20
1	00:00:01	-403	-131	20
1	00:00:02	-404	-131	20
1	00:00:03	-405	-131	20
1	00:00:03	-405	-130	20
1	00:00:04	-405	-129	20
1	00:00:05	-405	-125	20
...
```

Il présente respectivement les identifiants de différentes trajectoires, et leurs coordonnées (x,y,z) géographique et temporelle. Se référer à ce [lien](01_Familiarisation%20des%20données.ipynb) pour plus d'informations.  
Elles peuvent être erronées, ou sans erreur : celles qui sont erronées sont distinguées par la présentation de nombreux points autour d'une même zone.

Ce type de trajectoire ne devrait être présent et utilisé à l'échelle des entreprises. L'objectif est donc de pouvoir detecter ces trajectoires dites erronées, pour ainsi les nettoyer.


# Déroulement

Une première étape sera de comprendre ces jeu de données, en utilisant le python (plus précisément la librairie matplotlib, outil de visualisation de donnée), et de se famliariser avec les différentes librairies mises en oeuvre.

Dans un deuxième temps, une tentative de détection de données errornées se réalisera, en s'inspirant de celles qui ne le sont pas, et qui serviront de référence.

Ce n'est que par la suite que la correction des trajectoires erronées va être mise en place.

# Travaux réalisés/en cours

[Connaissance des jeux de données et des différentes libraries Python (Pandas et Matplotlib)](01_Familiarisation%20des%20données.ipynb)  
[Mise en place d'hypothèse de reconnaissances des trajectoires erronées](02_Détection%20des%20erreurs.ipynb)

# Dates

| Dates | Tâches |
| :---: | :---: |
| 05/02 > 09/02 | Choix des librairies et outils graphiques |
| 12/02 > 28/02 | Familiarisation de l'outil graphique et jeux de données (Python) |
| 21/02 > 19/03 | Mise en place d'une regle de référence/Détection d'erreurs sur une partie du jeu de donénes(Python) |
| 19/03 > 02/04 | Portage du code Python vers Python Notebook |
| 02/04 > 23/04 | Test de détection sur la totalité du jeu données/améalioration |
| 23/04 > 05/05 | Mise en place d'un système de nettoyage |
| 06/05 > ... | Début des préparation orales du projet (poster...) |