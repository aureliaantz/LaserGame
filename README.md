# LaserGame

  Notre projet consiste à créer un jeu de tire permettant à l’utilisateur de dévier le rayon 
d’un laser dans un terrain de sorte à éviter les murs et atteindre la cible.

![Capture d’écran 2022-02-04 090527](https://user-images.githubusercontent.com/93881768/152493602-171dab06-fb48-40ec-99e8-8a34e987e247.png)


## Laser et cible
  
  Le laser et la cible sont placée aléatoirement sur les côtés du terrain. On a fait en sorte 
que le laser et la cible ne soit pas placé sur la même case du contour de terrain (c’est-à-dire 
qu’il ne se superpose pas).

## Miroirs

  Des miroirs seront ensuite placés par l’utilisateur lui-même pour lui permettre de 
modifier la direction du laser. Là aussi on a fait en sorte que les miroirs ne soit pas placé sur 
les cases sur terrains (le contour du terrain) mais plutôt à l’intérieur du terrain. Selon le type 
de miroir posé (soit un miroir « / », soit un miroir « \ »), le laser sera alors dévié.

## Murs

  De plus, des murs seront placés aléatoirement dans le terrain mais tout en évitant que 
les murs se place devant le laser ou la cible car sinon le jeu serait perdu sans même 
commencer. Ensuite, le joueur devra placer les miroirs de sorte que le laser ne rencontre pas 
de murs (obstacles) jusqu’à la cible.
Le code devra également pouvoir permettre à l’utilisateur d’importer un terrain déjà 
existant ou encore de créer lui-même son propre terrain.
