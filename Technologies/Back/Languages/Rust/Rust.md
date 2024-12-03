Langage de programmation de très bas niveau, comparable au C, où l'on doit gérer soi-même sa mémoire

## Avantages

 * Un borrow checker à la place d'un garbage collector
 * Hyper optimisé au niveau des performances lorsque l'on code correctement
 * Null safe
 * Gestion très pratique des erreurs
 * Langage hyper expressif
 * Rocket est un framework web qui utilise au mieux les macros et permet donc de limiter la quantité de boilerplate pour les API REST
 * Sympa à coder
 * Rust Rover est une excellente IDE

## Inconvénients

 * Un borrow checker à la place d'un garbage collector
 * Apprentissage complexe
 * Du mauvais code Rust n'est pas optimisé, on clone tout
 * La gestion des opérations concurrentes est une horreur
 * Les lifetimes (nécessaires pour l'optimisation) sont une abstraction rendant difficile le refactoring des types
 * Pas de support par Google pour les protobufs. On se retrouve obligé d'utiliser une [librairie tierce](https://github.com/stepancheg/rust-protobuf) dont la maintenance n'est pas assurée
 * Le LSP prend trente ans à démarrer et réquisitionne la moitié de ta RAM
 * Le projet prend quarante ans à compiler, ce qui n'est pas très adapté pour une très grosse application
 * Dépendances importante à des librairies tierces pour beaucoup de choses basiques comme le fait de parse du JSON.

Liens :
* [[Rocket]]
* [[Rust protobuf]]