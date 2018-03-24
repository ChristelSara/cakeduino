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

- Séance du 8 janvier 2018

Durant cette deuxième séance, nous avons été à la recherche d'un plotter XY qui sera la base de notre projet, de seringues, d'un moteur qui poussera la seringue qui libérera de l'air qui fera pousser la crème qui sera présenter dans la douille (inspiré du bras hydraulique, voici un exemple : https://www.youtube.com/watch?v=P2r9U4wkjcc)

- Séance du 15 janvier 2018

Durant cette troisième séance, nous avons finalement décidé d'utiliser une imprimante 3D où on utlisera les 3 axes (vertical, horizontal (devant/derrière), horizontal (gauche/droite)). En effet, si nous voulons un beau rendu et pouvoir faire plus de choses, il est préférable de se servir de l'axe vertical. Ainsi, nous avons donc cherché une imprimante 3D à commander. 
Nous avons réfléchi au système qui permettra à la douille de verser son contenu de façon autonome. Avec l'aide du professeur M.Masson, nous nous sommes inspirés du bras hydraulique et nous avons donc trouvé comment nous allons procéder : après avoir reçu une commande via Arduino, un moteur pas à pas poussera une première seringue qui contient de l'air, cet air passera par un tube et arrivera dans une seconde seringue (placée à l'envers) qu'il poussera. Comme la seconde seringue sera accrochée/collée à la douille (sous forme de seringue de pâtisserie), elle poussera cette dernière qui versera son contenu sur le gâteau. [se référer aux schémas pour plus de clarté] Nous aurons 4 douilles donc il faudra monter ce système 4 fois. Ainsi, nous avons cherché des seringues, des douilles et des moteurs pas à pas à commander. 

Il nous reste à voir comment fonctionne le moteur pas à pas avec Arduino, comment accrocher les 4 douilles à l'imprimantes 3D, comment construire les 4 structues qui soutiendront le système "bras hydraulique" afin que ces structures puissent suivre la douille qui se déplacera pendant qu'elle décorera le gâteau. Il faudra aussi s'occuper du code pour l'imprimante 3D. 

- Séance du 22 janvier 2018

Nous avons fait fonctionner le moteur pas à pas avec arduino et nous avons réfléchi à comment nous allons faire marcher le moteur avec la seringue. Pour cela, nous allons nous menir d'une crémaillère et d'un pignon. La seringue sera "collée" sur la crémaillère et le pignon sera accroché sur la "roue" du moteur. L'engrenage du pignon sera emboîté avec la crémaillère et ainsi, lorsque le moteur tournera, il poussera la seringue.

Nous avons donc cherché durant la séance des crémaillères et des pignons car il nous en faut 4 (une par structure).

- Séance du 7 février 2018

Nous avons reçu les 4 douilles et les 4 moteurs pas à pas que nous avions commandés. Nous avons commandé l'imprimante 3D et les seringues avec leur tube.
Nous avons réfléchi plus en détails à quels choix seront proposés par le client pour décorer son gâteau commme ça nous pourrons attaquer le code dès que nous recevrons l'imprimante 3D.

<img src="https://ae01.alicdn.com/kf/HTB1p5SihzihSKJjy0Fiq6AuiFXa9/SZS-Chaude-De-D-coration-De-G-teau-D-corateur-Avec-8-Conseils-Buses-Givrage-Seringue.jpg_640x640.jpg" width="150"> <img src="https://ae01.alicdn.com/kf/HTB15xzKg_nI8KJjSszbq6z4KFXaP/CE-ROSH-57HB41-401A-Stepper-moteur-couple-0-64N-M-Phase-actuelle-2-4A-pour-quipements.jpg" width="150">

- Séance du 4 février 2018

Nous avons reçu l'imprimante 3D (AnetA8) ainsi nous avons commencé à la monter.

- Séance du 21 mars 2018

Nous avons avancé le montage de l'imprimante 3D en dehors des séances (3h) et nous avons continué à la monter durant cette séance également. Le montage de l'imprimante 3D prend du temps car il n'y a pas de notice officielle donc nous devons nous débrouiller avec les instructions que nous trouvons sur Internet. Nous utilisons ce site : https://www.zvoon.net/imprimante-3d/montage-anet-a8-assemblage-prise-main/ et nous nous aidons parfois de vidéos sur Youtube quand nous ne comprenons pas ce que le site nous dit. 
Nous avons reçu les seringues et leur tube. 
