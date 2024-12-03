Technologie utilisée pour payer à la computation plutôt qu'à l'utilisation d'un serveur.

Avantages :
 * Pas de client, pas de charges à payer.
 * Hébergement managé et scalable d'un point de vue technique, dans le sens où seul la facture va grossir à mesure que des personnes utiliseront l'application
 * Le fait d'utiliser des APIs pour toutes les fonctionnalités nécessitant un hébergement serveur assure une qualité et une sécurité de pointe pour toutes ces opérations critiques et complexes (authentification, upload de fichiers)
 * Plus le code est optimisé, moins il y a de computations, moins il y a à payer

Inconvénient
 * Pas adapté pour un serveur utilisant une base de données, puisqu'il faudra de toute façon héberger la base de données quelque part
 * Demande d'utiliser des API payantes pour faire des choses que seul un serveur peut faire : stocker des fichiers, s'occuper des sessions utilisateurs, gérer une base de données.
 * Obligation d'utiliser Typescript / Javascript pour le backend.
 * Si l'application scale en utilisateurs sans que l'on ai trouvé de moyen de monétiser, on peut se retrouver avec des factures absurdes.
 * Couteux à scale.