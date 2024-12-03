ORM de base de go

Permet de faire un peu de requêtes natives.

Globalement, l'idée est d'optimiser la partie back, on peut donc être tenter d'éviter d'utiliser un ORM pour pouvoir s'assurer de ne jamais récupérer plus que ce que l'on a besoin, et toujours connaitre et maitriser l'exécution des différentes requêtes SQL

## Avantages:

 * Rapidité de développement
 * Les différents types de données en Go et les pointeurs permettent une génération assez fine des contraintes sur les colonnes
 * Systèmes d'auto update
 * Pas besoin d'écrire de SQL

## Inconvénient

 * Configuration complexe pour optimiser les requêtes, et ne sera jamais aussi efficient qu'une requête SQL construite spécialement pour faire exactement ce qu'elle doit
 * Système d'annotation des fields un peu bordélique pour la création des contraintes et des associations

[Lien de la doc](https://gorm.io/docs/)