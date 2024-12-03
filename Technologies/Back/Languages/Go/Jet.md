Query builder pour go, extrêmement performant, s'écrit un peu comme du SQL. Totalement Typesafe. Probablement le meilleur query builder tout langage confondu.

## Avantages 
 * Totalement typesafe
 * Se transcris en SQL parfaitement lisible
 * Offre un outil de génération de code à partir de la base, ce qui permet de créer sa base en SQL pur plutôt que l'inverse proposé par les ORMs. Permet donc d'optimiser la base de données au niveau même de sa conception.
 * Permet de faciliter l'utilisation de la concurrence lorsque l'on effectue plusieurs requêtes.

## Inconvénients
 * Plus lent d'écrire ses requêtes SQL que d'utiliser un ORM
 * Mapping des résultats parfois complexe lorsque l'on fait des requêtes avec jointures

[Lien du github](https://github.com/go-jet/jet)

[Lien pour le mapping dans les structures](https://github.com/go-jet/jet/wiki/Query-Result-Mapping-(QRM)#custom-model-types)