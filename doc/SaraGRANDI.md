# Cahier de suivi du projet de Sara GRANDI
- Le 18/12/2017                                 

Je suis en binôme avec Ralalasoa Christel . On a décidé de faire un décorateur de gâteau avec Arduino par le biais d'une imprimante 2D. Mais de base on était plutôt sur le fait de faire un machine à Barbe a papa . Mais comme la machine à barbe a papa commerciale n'est pas tres efficace on a changé de projet.

![alt tag](https://www.themadeco.fr/img/scenes/29-scene_v2.jpg)

On se tourne donc vers un décorateur de pâtisserie, il sera utilisé de la façon suivante :

On posera un base de gateau (génoise etc..) et grâce au information donnée on va utiliser des seringues pour dessiner et décorer avec de la garniture le gâteau . C'est a dire qu'on va par exemple ordonner a l'imprimante via Arduino avec la forme du gâteau , la quantité de crème ainsi que les dimensions de la base pour que les ingrédients qui servent a décorer ne dépassent pas la base du gâteau.

A la base on comptait utiliser des douilles de pâtisserie pour décorer le gâteau mais pour des raisons techniques et de faciliter on va utiliser des seringues pour que la crème soit repartit de manière plus uniforme et plus controlé.

Durant cette séance on s'est consacrer à la recherche d'imprimante 3D qui est notre préoccupation principale . On a définit quelque rôles mais rien n'est encore fixe . On a pensé que une de nous deux se consacrerait plutôt au code de l'imprimante et l'autre plutôt au montage de l'imprimante. Je pense que je m'occuperais du code et Christel plutôt du montage .

Les courses à faire :

– Kit imprimante 3D (mais on utilise que 2 axes)
– Seringues ( 4 ou 5 )
– Crème (je le préparerais)
– Base gâteau (je le préparerais)

Les choses à faire:

– Faire l' imprimantes 2D
– Ecrire le code Arduino
– Mécanisme qui va appuyer sur la seringue pour faire descendre une dose de crème
– Penser a écrire le compte rendu chaque semaine.

Pendant le prochain cour :

– Continuer la recherche d'imprimante 3D et passer la commande
– Trouver les seringues de même
– Penser à comment écrire le code

- Le 08/01/2018 :

Nous avons , durant cette séance decider d'utiliser un plotter XY au lieu d'une imprimante 2D. En effet le plotter XY nous permettra de décorer le gateau de facon plus simple . Nous avons chercher sur amazon, aliexpress et d'autre site des plotter XY. De plus pour que ce soit plus pratique a l'utilisation , sachant qu'un plotter XY s'assemble avec 4 segment pour faire un carrée on a décider d'enlever un segment pour pouvoir faire un plateau pour pouvoir y déposer le gateau à décorer.

![alt tag](https://www.robotshop.com/media/files/images2/makeblock-xy-plotter-robot-kit-no-electronics-desc1.jpg)

Mais aussi grace au conseils de M. Masson,nous nous interresseront aussi au bras robot hydraulique mais en le transformant légerement et au lieu de l'utiliser avec l'eau on va plutot l'utiliser avec de l'air. C'est a dire que les seringues qui articulent le bras seront remplis d'air et non d'eau. On y ajoutera des servo-moteurs pour pouvoir commander le pas de la descente de la ganache dans la seringue .

![alt tag](https://i.pinimg.com/736x/ca/f4/db/caf4db8eab444065206d962a3e65ea17--robot-arm-model-kits.jpg)

Durant cette séance nous avons aussi chercher des seringues qui pourrait contenir une assez grande quantité de ganache pour decorer un gateau. De plus on envisage d'installer plussieurs seringues sur le plotter XY comme ca le client aura plus de choix .

![alt tag](https://www.cuisinstore.com/media/imageCMS/seringue-a-decorer-inox-1307-350x350.jpg)

La semaine prochaine on va essayer de enfin commander le materiel nécessaire et de penser au code .

- Le 15/01/2018:

 Durant cette semaine on à decider de remplacer le plotter XY par une imprimante 3D car c'est plus pratique pour pouvoir faire des dessins avec altitude. De plus on a compris le fonctionnement du bras hydraulique et donc on va le constrire nous meme avec des seringues et du bois . Comme on a decidé de mettre 4 poches à douilles dans l'imprimante 3D il faut donc 4 bras avec deux seringues dans ce bras c'est a dire 8 serigue de 100 ml pour que la poussée soit assez importante pour pousser la ganache dans les poches a douille (voir schéma).
 
 ![alt tag](https://images-na.ssl-images-amazon.com/images/I/51jeIWHUKML._SY542_.jpg)
 
 https://www.amazon.fr/Zeller-42804-Seringue-Plastique-Transparent/dp/B007XSTG2A/ref=pd_sbs_201_5?_encoding=UTF8&psc=1&refRID=479TC2WVVQNBJQK4XTMX  (poche à douille)
 
 On va notamant commander des servo-moteurs pour controler le bras hydraulique.
 Pour la prochaine scéance il faut faire une presentation à l'oral et on va notament essayer de passer les commandes des seringues des douilles des tubes et des servo-moteur.
 Et pendant le temps restant on s'occupera à reflechir de comment utiliser les servo-moteurs avec arduino.
 
 - Le 22/01/2018:
 
 Durant cette scéance on a presenté l'avancée de notre projet devant la classe et les professeurs et aussi ecouté l'avancée du projet de nos camarades. On peut retrouver le diapo sous forme pdf que l'on a presenté dans le dossier doc . Apres les presentations il restait 1 heure et durant cette heure on a chercher sur ebay quelque materiel et sous le conseil de M.Masson on a decider d'utiliser le systeme de pignon et crémaillere dans le mecanisme du bras hydraulique au niveau de la premiere seringue . Il nous en faudra 4 c'est a dire un pour chaque bras .
 
  ![alt tag](http://www.hellopro.fr/images/produit-2/8/8/3/pignon-a-denture-trempee-alese-clavete-5879388.jpg)
  
  Avec le moteur pas a pas qui va pousser la seringue :
  
  ![alt tag](http://img.directindustry.fr/images_di/photo-g/8191-5112265.jpg)
  
  Durant la semaine de vacances je vais essayer de voir comment programmer le moteur pas a pas pour qu'on puisse lui rentrer un nombre de pas et qu'il avance de ce nombre de pas .

- Le 07/02/2018:

 Aujourd'hui nous avons eu 1H30 de tp et on a recu les 4 seringues à douilles ainsi que les 4 moteur pas a pas . De plus monsieur Masson nous a commander l'imprimante 3D. Nous avons donc reflechis a quelles types de gateau le cakeduino fera et esquisser quelque croquis . De plus avec mon binome on a convenu que nous irons au Fablab pour faire les pignons et cremailleres . La semaine prochaine nous nous concentrerons sur le programme et se concentrer sur la reel fonction du cakeduino car ce que nous voulions faire etais trop vaste.
 
 
