# Altervilles open data

## Le projet

Cet espace de travail collaboratif est alimenté par les étudiants du master Altervilles et Copter, dans le cadre du cours Ville numérique.
Il a vocation à héberger des jeux de données constitués par les étudiants, ainsi que leur documentation associée.

**Objectif : créer et mettre à disposition des jeux de données qui ne sont pas publiés par les collectivités territoriales stéphanoises.**

## Les données

Plusieurs jeux de données sont identifiés :

### Délibérations de la métropole de Saint-Etienne

#### Où se trouvent les données ?

Les délibérations [se trouvent ici](https://www.saint-etienne-metropole.fr/la-metropole/vie-democratique/deliberations)
Une liste des délibérations existe, mais ce n'est pas un jeu de données exploitable. 

#### Quel est le périmètre des données à constituer ?

Nous allons nous concentrer sur les délibérations de 2022 (soit 108 délibérations entre le 20-01-2022 et le 24-03-2022)

#### Où se trouve le modèle de fichier à créer ?

Le modèle de fichier à créer se trouve ici

#### Précisions sur les données

- Le champ `DELIB_MATIERE_CODE`ne peut pas être complété, car il n'est pas précisé dans les délibérations
- Le champ `DELIB_MATIERE_NOM`est à interpréter, à partir du l'objet de la délibération et de cette nomenclature [existante dans une autre administration](http://www.moselle.gouv.fr/content/download/1107/7994/file/nomenclature.pdf). Exemple : COMMANDE PUBLIQUE
- Le champ `VOTE EFFECTIF` = Nombre de membres en exercice
- Le champ `VOTE REEL`= Nombre de présents
- Si la délibération est adoptée à l'unanimité, alors `VOTE POUR`= Nombre de voix
