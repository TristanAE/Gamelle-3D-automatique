# Gamelle-3D-automatique

Modélisation gamelle avec déclenchement automatique.


# I-	Modélisation 3D

a)	Bloc principal

Pour modéliser cet objet, il a fallu le décomposer en plusieurs éléments puis venir les coller ensemble. Le matériau utilisé est le PLA.
Le temps nécessaire est de 12h00 pour le bloc principal.

 ![Image1](https://user-images.githubusercontent.com/92324336/139713631-d639aa89-8577-435a-a0ba-eaf5f5679d47.png)



Le bloc est un cube de 10cm de côté .
Sa partie inferieure est constituée d’une pente permettant le glissement des croquettes jusqu’à la zone accessible pour les animaux (non visible).
Sur son coté droit, une fente permet de glisser la trappe ce qui permettra aux croquettes de descendre ou non.
Les deux trous au sommet ont des rôles différents : l’un permet de voir le mécanisme et sera fermé par un toit, l’autre est formé d’une pente pour mettre les croquettes et que celles-ci puissent glisser jusqu’à a trappe.
Un mur sépare les deux zones pour que les croquettes allant se déposer sur la trappe ne soit pas trop nombreuses et ne surchargent le mécanisme.
 
![Image2](https://user-images.githubusercontent.com/92324336/139713645-4869f250-7662-4f96-969a-2aacf4df4efa.png)

 

La longue fente de forme cylindrique à l’arrière devait permettre à l’ouverture de la trappe de fonctionner comme une porte par méthode du gond : uniquement une partie de la trappe devait s’affaisser tendis que l’autre restait droite. Apres réalisation de la structure en 3D, cette technique n’a pas fonctionnée.
Les parallélépipèdes dans la fente servent de piliers et permettent de faire fonctionner l’impression 3D correctement en ne laissant pas de vide.

Le trou sur le coté permet de placer un servomoteur et de le coller sur la trappe pour mouvoir celle-ci.

![Image3](https://user-images.githubusercontent.com/92324336/139713659-ede1eb55-d2e8-4342-aa84-455c9b9d815b.png)




b)	Eléments secondaires

 
![Image4](https://user-images.githubusercontent.com/92324336/139713680-45be5f0c-636d-4fa2-a3ff-32e34b36fcdb.png)


Le 1er élément visible est la gamelle, la zone ou des croquettes arrivent et sont accessibles pour les animaux. Elle vient se coller sur la face du bloc principal.
Le 2ème élément est un supplément de hauteur pour la pente du haut : Apres réalisation de la structure 3D, la pente n’était pas assez raide pour faire descendre correctement les croquettes.
Le 3ème élément est une fermeture sur la face du bloc



 ![Image5](https://user-images.githubusercontent.com/92324336/139713758-6466276e-53d2-4478-a894-20cac5c898fd.png)


Le toit permet de cacher le mecansime et la trappe vient se glisser dans le trou situé sur le coté du bloc. Sa partie cylindriue devait permettre de fonctionner comme un gond.


# II-	Mécanisme de la trappe

La trappe s’abaisse pour faire descendre les croquettes puis remonte pour bloquer les suivantes. 
Un chronomètre est lancé au branchement du mécanisme : toutes les 5h00, la trappe s’abaisse pendant 3 secondes puis remonte. Le chronomètre est ensuite reinitialisé et ainsi de suite.

![ezgif com-gif-maker (1)](https://user-images.githubusercontent.com/92324336/139714917-4bc87b61-6a8e-4eb2-909e-73fd548a588d.gif)

