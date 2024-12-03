Moyens techniques utilisés pour créer l'application.

 * [[Back]]
 * [[Front]]
 * [[DevTools]]
 * [[Devops]]

Globalement les guidelines sont les suivantes:

 - En ce qui concerne les technologies utilisées, les compétences en développement sont les choses les moins chères de l'application, puisque je vais travailler dessus. L'idée est donc de ne pas prendre des technologies qui peuvent devenir très chères pour tenter d'économiser sur la quantité de développement ou de connaissances requises : je développe et apprend vite, j'ai des connaissances solides sur les bases du développement, et je suis suffisamment autiste pour coder 10 heures par jour.
 
 - On cherche une scalabilité moyenne du fait d'un marché principalement situé en France. Le but est d'essayer d'économiser sur les outils de développement, et de mettre le paquet sur l'optimisation des performances du code backend, quitte à être peu efficient dans la vitesse du développement. On ne s'attend pas à avoir un million d'utilisateur dès le début, et ce n'est de toute façon pas un réseau social : les gens ne seront pas en permanence sur l'application. Le modèle de monétisation de l'application n'est également pas basée sur la rétention de l'attention, il n'y a donc pas un besoin de fournir énormément de contenu à énormément d'utilisateurs. On cherche toutefois, en tant que startup, à pouvoir itérer suffisamment rapidement sur l'application sans avoir à changer un million de choses différentes pour chaque nouvelle feature ou correction de bugs.

 * La sécurité doit évidemment être totalement irréprochable. On essaie donc d'introduire le moins possible d'environnements dont je ne connais pas les tenants et aboutissants en terme de sécurité.
 
 - On cherche l'efficience raisonnable du front. On peut se permettre quelques écarts de performance sur le front, tant qu'ils n'impactent pas l'expérience utilisateur. Ceci, comme toute application de gestion, les délais doivent être très réduis, et les temps de chargement le moins long possible, voir inexistants. On peut cependant se permettre un peu d'abstractions pour ne pas avoir à coder la même application plusieurs fois.
 