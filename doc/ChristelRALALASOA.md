# Cahier de suivi du projet de Christel Ralalasoa
- Séance du 18 décembre 2017

Durant cette première séance, mon binôme et moi avons discuté des différentes idées que nous avions en tête pour le projet. Tout d’abord, nous voulions faire une machine à barbe à papa automatisée mais le problème était que les machines en vente à un bas prix faisaient des barbes à papa trop petites. Nous avons donc opté pour une imprimante décoratrice de gâteaux.

![Gateau](https://www.berries.com/blog/wp-content/uploads/2016/01/hero-cake-decorating.jpg "Gateau")

En effet, nous nous munirons d’une imprimante 3D que nous « transformerons » afin qu’elle puisse décorer, selon les choix que le ‘client’ fera, un gâteau. Pour cela, il faudra :

* Acheter une imprimante 3D sur laquelle nous utiliserons seulement deux axes (l’axe vertical nous sera inutile étant donné que nous décorerons en 2D)
* Acheter des seringues que nous remplierons de crèmes (de différentes couleurs) qui serviront à décorer le gâteau. (Nous voulions à la base utiliser des douilles mais par soucis de facilité et de technique, il était finalement plus judicieux de choisir des seringues pour répartir la crème de façon uniforme sur le gâteau.)
* Ecrire un code qui permettra à l’imprimante de décorer le gâteau selon les choix du client. Ce code prendra donc en compte les coordonnées polaires du gâteau (pour que la décoration ne déborde pas), la quantité de crème contenue dans les seringues, etc.
    
Nous imaginons que nous allons devoir également utiliser une application avec un bluetooth pour que ces données soient envoyées via l’Arduino à l’imprimante.

Après avoir discuté de cette idée de projet, nous nous sommes consacrés à la recherche d’une imprimante 3D sur des sites marchands afin de pouvoir nous la procurer le plus tôt possible.
    
Enfin, nous avons essayé de définir quel serait le rôle de chacun. Je pense que je m’occuperai plutôt du montage de l’imprimante et Sara du code. 

- Séance du 8 janvier 2017

Durant cette deuxième séance, nous avons été à la recherche d'un plotter XY qui sera la base de notre projet, de seringues, d'un moteur qui poussera la seringue qui libérera de l'air qui fera pousser la crème qui sera présenter dans la douille (inspiré du bras hydraulique, voici un exemple : https://www.youtube.com/watch?v=P2r9U4wkjcc)

- Séance du 15 janvier 2017

Durant cette troisième séance, nous avons finalement décidé d'utiliser une imprimante 3D où on utlisera les 3 axes (vertical, horizontal (devant/derrière), horizontal (gauche/droite)). En effet, si nous voulons un beau rendu et pouvoir faire plus de choses, il est préférable de se servir de l'axe vertical. Ainsi, nous avons donc cherché une imprimante 3D à commander. 
Nous avons réfléchi au système qui permettra à la douille de verser son contenu de façon autonome. Avec l'aide du professeur M.Masson, nous nous sommes inspirés du bras hydraulique et nous avons donc trouvé comment nous allons procéder : après avoir reçu une commande via Arduino, un moteur pas à pas poussera une première seringue qui contient de l'air, cet air passera par un tube et arrivera dans une seconde seringue (placée à l'envers) qu'il poussera. Comme la seconde seringue sera accrochée/collée à la douille (sous forme de seringue de pâtisserie), elle poussera cette dernière qui versera son contenu sur le gâteau. [se référer aux schémas pour plus de clarté] Nous aurons 4 douilles donc il faudra monter ce système 4 fois. Ainsi, nous avons cherché des seringues, des douilles et des moteurs pas à pas à commander. 

Il nous reste à voir comment fonctionne le moteur pas à pas avec Arduino, comment accrocher les 4 douilles à l'imprimantes 3D, comment construire les 4 structues qui soutiendront le système "bras hydraulique" afin que ces structures puissent suivre la douille qui se déplacera pendant qu'elle décorera le gâteau. Il faudra aussi s'occuper du code pour l'imprimante 3D. 

