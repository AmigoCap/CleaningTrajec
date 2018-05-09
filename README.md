# Contexte

L'avancée technologique nous permet aujourd'hui de modéliser à travers des détecteurs la position d'un appareil mobile (e.g. persone, avion, voiture etc).
La récolte de ses données nous permet certes d'avoir une vision globable de sa trajectoire, mais il arrive qu'il y ait des erreurs de détection.

Le but ici est, en utilisant un certain de jeu de données, de pourvoir détecter ces erreurs de trajectoires.


# Déroulement

Une première étape sera de comprendre ces jeu de données, en utilisant le python (plus précisément la librairie matplotlib, outil de visualisation de donnée), et de se famliariser avec les différentes librairies mises en oeuvre.

Dans un deuxième temps, une tentative de détection de données errornées se réalisera, en s'inspirant de celles qui ne le sont pas, et qui serviront de référence.

Ce n'est que par la suite que la correction des trajectoires va être mise en place.

# Travail réalisé

[Connaissance des jeux de données et des différentes libraries Python (Pandas et Matplotlib)](01_Familiarisation%20des%20données.ipynb)

[Mise en place des hypothèses de reconnaissances des trajectoires erronées](02_Détection%20des%20erreurs.ipynb)

# Dates

| Dates | Tâches |
| :---: | :---: |
| 05/02 > 09/02 | Choix des librairies et outils graphiques |
| 12/02 > 28/02 | Familiarisation de l'outil graphique et jeux de données (Python) |
| 21/02 > 19/03 | Mise en place d'une regle de référence/Détection d'erreurs sur une partie du jeu de donénes(Python) |
| 19/03 > 02/04 | Portage du code Python vers Python Notebook |
| 02/04 > 23/04 | Test de détection sur la totalité du jeu données/améalioration |
| 23/04 > 05/05 | Mise en place d'un système de nettoyage |
| 06/05 > ... | Début de préparation orale du projet (poster...) |