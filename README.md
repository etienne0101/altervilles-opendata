# Altervilles open data

## 💡 Le projet

Cet espace de travail collaboratif est alimenté par les étudiants du master Altervilles et Copter, dans le cadre du cours Ville numérique.
Il a vocation à héberger des jeux de données constitués par les étudiants, ainsi que leur documentation associée.

**Objectif : créer et mettre à disposition des jeux de données qui ne sont pas publiés par les collectivités territoriales stéphanoises.**

## 🛠 Organisation

### Deux rendus sont attendus pour chaque groupe

- [🔎 Un jeu de données finalisé](#-les-données)
- [📖 Une documentation](#-la-documentation)

### Comment organiser le travail ?

- Chaque groupe travaille sur un des jeux de données proposés
- L'édition du jeu de données est répartie dans le groupe pour alléger le travail
- Chaque groupe a un référent, qui sera chargé de publier le fichier finalisé sur github

## 🔎 Les données

Plusieurs jeux de données sont identifiés :

### Délibérations de la Métropole de Saint-Etienne

#### Où se trouvent les données ?

Les délibérations [se trouvent ici](https://www.saint-etienne-metropole.fr/la-metropole/vie-democratique/deliberations)
Une liste des délibérations existe, mais ce n'est pas un jeu de données exploitable. 

#### Quel est le périmètre des données à constituer ?

Nous allons nous concentrer sur les délibérations de 2022 (soit 108 délibérations entre le 20-01-2022 et le 24-03-2022)

#### Où se trouve le modèle de fichier à créer ?

Le modèle de fichier à créer se trouve ici

#### Précisions sur les données

- Le champ `DELIB_MATIERE_CODE`ne peut pas être complété, car il n'est pas précisé dans les délibérations
- Le champ `DELIB_MATIERE_NOM`est à interpréter, à partir de l'objet de la délibération et de cette nomenclature [existante dans une autre administration](http://www.moselle.gouv.fr/content/download/1107/7994/file/nomenclature.pdf). Exemple : COMMANDE PUBLIQUE
- Le champ `VOTE EFFECTIF` = Nombre de membres en exercice
- Le champ `VOTE REEL`= Nombre de présents
- Si la délibération est adoptée à l'unanimité, alors `VOTE POUR`= Nombre de voix

### Marchés publics de la Métropole de Saint-Etienne

#### Où se trouvent les données ? 

1. Je vous laisse chercher "Marchés publics Saint Etienne Métropole" dans Google
2. Vous allez arriver sur une page qui vous permettra de faire une recherche avancée.
3. Dans la recherche avancée, vous allez pouvoir sélectionner "Données essentielles".
4. Cliquez sur rechercher
5. Téléchargez les données de consultation

<details><summary>Indice</summary> C'est ici :https://www.saint-etienne-metropole.fr/etudier-entreprendre/entreprises/marches-publics </details>

## 📖 La documentation

En supplément du jeu de donnée constitué par votre groupe, vous produisez une courte documentation (l'équivalent d'une ou deux pages maximum).

Elle détaille :

### Le jeu de donnée et l'objectif de sa publication

- Quel est le jeu de données ?
- Quelles données contient-il ? (expliquez comme vous le feriez à un lycéen)
- Quel est le périmètre / l'étendue des données (géographique et ou temporel)
- À quoi peuvent servir ces données ? (en trois lignes maximum)

### Votre méthode

- Quelle est la source des données ?
- Quels outils avez-vous utilisé ?

### Vos difficultés

- Est-ce que la source des données vous a permis de constituer le jeu de données que vous souhaitiez ?
- Est-ce que c'est incomplet ? Pourquoi / qu'est-ce qu'il vous a manqué ?
- Autre chose ?

### Conclusion libre

- Quelque-chose vous semble important ou utile à ajouter ?

## Critères d'évaluation - pour chaque groupe

### Qualité des données (10 pts)

- Un fichier CSV a été déposé sur Github - (2 pts)
- Les données sont exploitables (la structure est respectée) - (2pts)
- Même s'il peut manquer des données, vous avez fait votre possible pour constituer un fichier le plus complet et le plus correct possible - (6 pts)

### Qualité de la documentation (7 pts)

- Une documentation accompagne votre jeu de données (2 pts)
- Vous avez détaillé correctement le contenu du fichier (2 pts)
- Vous avez exposé vos difficultés et vos éléments de méthode (3 pts)

### Organisation et méthode (3 pts)

- Votre groupe a fourni les éléments dans le délai demmandé (1 pt)
- Vous avez sollicité de l'aide si c'était nécessaire ! (2 pts)
