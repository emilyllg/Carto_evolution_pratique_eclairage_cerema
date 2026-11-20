# Éclairage nocturne : changements de pratique par commune

Cartographie réalisée sous QGIS à partir de données du Cerema sur l'éclairage public nocturne en France, de 2014 à 2025.
## Sources

- Jeu de données : [Cartographie nationale des pratiques d'éclairage nocturne](https://ecologie.data.gouv.fr/datasets/cartographie-nationale-des-pratiques-declairage-nocturne) (Licence Ouverte 2.0)
- Rapport technique (PDF): [Développement d'un outil de détection de l'extinction nocturne par données satellites VIIRS](https://ecologie.data.gouv.fr/datasets/cartographie-nationale-des-pratiques-declairage-nocturne)
Source des données : Cerema (Pôle satellite), DarkSkyLab, OFB.
Carte et mise en page : Emily-Jane Lelong.

> À COMPLÉTER : territoire cartographié et image de la carte

![Carte](maps/01_changements_pratique.png)

## Les données utilisées

Pour chaque commune, le jeu de données donne :

| Donnée | Valeurs | Unité |
|---|---|---|
| Luminosité mesurée depuis l'espace, chaque mois de 2014 à 2025 | un nombre par mois | nW·cm⁻²·sr⁻¹ (plus la valeur est haute, plus la commune émet de lumière vers le ciel) |
| Type de changement de pratique détecté | E, R, D, A, X, HT (voir ci-dessous) | sans unité |
| Date du changement | année et mois | |
| Population | nombre d'habitants | habitants |

Les types de changement :
- E : extinction de l'éclairage public très probable
- R : rénovation du parc d'éclairage et/ou extinction partielle
- D : extension de l'éclairage
- A : extension de l'éclairage et/ou abandon d'une extinction
- X : aucun changement détecté
- HT : commune non étudiée (trop peu lumineuse pour être vue par satellite)

## Ce que ressort des données

D'après le rapport du Cerema, sur 22 773 communes analysées depuis 2014 : 12 539 extinctions totales, 4 031 extinctions partielles, 459 abandons d'extinction et 856 extensions. Les extinctions sont surtout le fait de petites et moyennes communes, et se sont fortement accélérées en 2022.

À lire avec précaution : ce sont des détections probables faites par satellite, pas des confirmations.

## Sources

- Jeu de données : [Cartographie nationale des pratiques d'éclairage nocturne](https://ecologie.data.gouv.fr/datasets/cartographie-nationale-des-pratiques-declairage-nocturne) (Licence Ouverte 2.0)
- Rapport technique (PDF) : téléchargeable depuis la même page, sous le titre « Développement d'un outil de détection de l'extinction nocturne par données satellites VIIRS »

Source des données : Cerema (Pôle satellite), DarkSkyLab, OFB.
Carte et mise en page : Emily-Jane Lelong.
