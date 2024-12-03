Permet d'avoir une application native en ne l'écrivant qu'une seule fois. Permet même de faire du web.

[Lien du site officiel ](https://reactnative.dev/)

[Lien du repo github de BlueSky](https://github.com/bluesky-social/social-app)

[Lien d'un test entre react native et flutter](https://medium.com/@fmmagalhaes/i-built-the-same-app-with-flutter-react-native-and-ionic-33ff8b358562)

Demande de faire beaucoup de recherches sur la façon de fonctionner de React, et ensuite de chercher les spécificités de React Native, et ensuite de rechercher comment le build. Heureusement il y a du bon tooling.

### Avantages

 * Utilisation d'un langage (Typescript) que je connais déjà
 * Une collection de librairies gigantesques couvrant tous les cas d'utilisation possibles
 * Des librairies de très grande qualité fournies par expo pour les problèmes les plus communs.
 * Compile en natif, donc relativement performant
 * Syntaxe extrêmement claire concernant l'UI, grâce à la reprise du framework de description d'interface de React.
 * Permet de tester son application sur toutes les plateformes sans dépendre d'Android Studio et sans nécessiter d'avoir un MAC (juste un Iphone)
 * Expo EAS permet de gérer la publication de son application sur les différents stores.

## Inconvénients

 * Insupportable dans la gestion de dépendances
 * React force un paradigme fonctionnel dans la gestion de l'état des composants, parfois rendant impossible certaines choses qu'il serait aisée de faire avec trois lignes de pur javascript (ajouter un élément à une liste sans re-render totalement la liste (je déteste react))
 * N'est pas totalement du natif, donc moins performant qu'une application en Kotlin ou en Swift.

Technologies liées :

 * [[Expo]]
 * [[Expo EAS]]
 