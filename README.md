# Gamelle-3D-automatique
Modélisation gamelle automatique avec déclenchement à certains intervalles de temps.


# I-	Modélisation 3D

a)	Bloc principal

Pour modéliser cet objet, il a fallu le décomposer en plusieurs éléments puis venir les coller ensemble. Le matériau utilisé est le PLA.
Le temps nécessaire est de 12h00 pour le bloc principal.

 


Le bloc est un cube de 10cm de côté .
Sa partie inferieure est constituée d’une pente permettant le glissement des croquettes jusqu’à la zone accessible pour les animaux(non visible).
Sur son coté droit, une fente permet de glisser la trappe ce qui permettra aux croquettes de descendre ou non.
Les deux trous au sommet ont des rôles différents : l’un permet de voir le mécanisme et sera fermé par un toit, l’autre est formé d’une pente pour mettre les croquettes et que celles-ci puissent glisser jusqu’à a trappe.
Un mur sépare les deux zones pour que les croquettes allant se déposer sur la trappe ne soit pas trop nombreuses et ne surchargent le mécanisme.
 

 

La longue fente de forme cylindrique à l’arrière devait permettre à l’ouverture de la trappe de fonctionner comme une porte par méthode du gond : uniquement une partie de la trappe devait s’affaisser tendis que l’autre restait droite. Apres réalisation de la structure en 3D, cette technique n’a pas fonctionner et quand la trappe se baisse, l’autre côté se soulève.
Les parallélépipèdes dans la fente servent de piliers et permettent de faire fonctionner l’impression 3D correctement en ne laissant pas de vide.

Le trou sur le coté permet de placer un servomoteur et de le coller sur la trappe pour mouvoir celle-ci.





b)	Eléments secondaires

 

Le 1er élément visible est la gamelle, la zone ou des croquettes arrivent et sont accessibles pour les animaux. Elle vient se coller sur la face du bloc principal.
Le 2ème élément est un supplément de hauteur pour la pente du haut : Apres réalisation de la structure 3D, la pente n’était pas assez raide pour faire descendre correctement les croquettes.
Le 3ème élément est une fermeture sur la face du bloc


 

Le toit permet de cacher le mecansime et la trappe vient se glisser dans le trou situé sur le coté du bloc. Sa partie cylindriue devait permettre de fonctionner comme un gond mais cela n’a pas marché.


# II-	Mécanisme de la trappe

La trappe s’abaisse pour faire descendre les croquettes puis remonte pour bloquer les suivantes. 
Un chronomètre est lancé au branchement du mécanisme : toutes les 5h00, la trappe s’abaisse pendant 3 secondes puis remonte. Le chronomètre est ensuite reinitialisée et ainsi de suite.

Partie informatique :

On déclare tout d’abord les élements necessaires au servomoteur.
On déclare également deux variables : times et previous qui vont permettre de lancer un chronomètre et de le réinitialiser.
Times=millis() permet de lancer un chronometre dès que le système démarre.
Times=times-previous permet de reinitialiser le chronomètre lorsque, plus tard, previous aura pris la valeur de times.
Une condition tourne le servomoteur de 40 degrés puis attend 3 secondes et le remonte jusqu’à 0 degré. 
Lorsque la condition est remplie, il faut que le chronomètre se réinitialise. Previous prend donc la valeur de time.



