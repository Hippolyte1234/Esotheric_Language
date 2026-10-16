Je vais expliquer le programme tel que je l'ai conçu, dans l'ordre.
Le but du langage est de ressembler à une chanson, j'ai donc explicitement fait exprès de rendre le nom des variables vague et poétique (à mon niveau) ainsi que de structurer le code comme ceci.

Ligne 1 à 4:
Je définis Tommy égal à 28, puis Milou égal à 25. Je fais une soustraction entre Tommy et Milou pour obtenir Jack (3), et enfin j'incrémente Jack
Cela permet de définir une variable égale à 4 et d'utiliser un moyen un peu détourné qui utilise plusieurs moyens de calculs

Ligne 6 à 7:
Je définis Horror à 10 et Joy à 2
Encore une fois des variables qui me sont utiles plus tard (fonction racine carrée) et qui évitent d'écrire des nombres dans une chanson de rock

Ligne 9 à 18:
Je définis une fonction Midnight qui en réalité calcule la racine carrée d'un nombre (comme aucune fonction n'est implémentée pour faire ça en Rockstar) grâce à la méthode de Euler à 10 itérations.
Dans l'ordre: 
Je définis your_soul = à your_heart variable d'entrée, je définis un compteur à 0, puis une boucle while tant que compteur est < à 10 je divise your_heart par your_soul que je met dans la variable Quotient, j'aditionne Quotient et your_soul que je mets dans Total et enfin je divise Total par 2 que je remets dans your_soul et j'incrémente le compteur.
Finalement je return your_soul à la fin de la fonction

Ligne 20 à 31:
Je récupère à la suite 3 valeurs input par l'utilisateur dans les variables: Jolene, Michael et Joey que je cast en Integer.
Ces trois variables correspondent aux a,b,c de l'équation de recherches des solution à ax²+bx+c=0
Je met également la variable b au carré à la ligne 27 puisque her et he correspondent à la dernière variable définie.
Les parenthèses sont des commentaires visant à rendre le texte plus joli

Ligne 33:
Je calcule 4*a*c grâce à Jolene et Joey que je place dans la variable Other

Ligne 35:
Je calcule ensuite le discriminant delta avec Love - Other que je place dans la variable Content

Ligne 39 à 42:
Je prépare le calcul des racines en calculant tout d'abord -b dans Grass et 2*a dans Clouds

Ligne 44 à 49:
Je vérifie que Jolene (a) n'est pas nul car dans ce cas c'est une équationdu premier degré et je calcule donc Soil = -c/b que je print en tant que réponse

Ligne 51 à 54:
Début et première partie de la Condition, ie correspond au si delta = 0.
Je définis alors Sun comme -b/2*a et je print La réponse est suivi de Sun

Ligne 56 à 65:
La deuxième et majeure partie du calcul: quand delta est positif et que l'on a 2 racines réelles.
Je vérifie donc que delta est > 0, puis je j'utilise la fonction Midnight (racine carrée) pour calculer racine(delta) que je place dans la variable Running, puis je Mets l'inverse dans Desperation
Je calcule ensuite l'addition de Grass et Running dans Scenery puis Grass et Desperation dans Landscape
Et enfin, je calcule les deux solutions avec la division de Scenery par Clouds(-b+sqrt(delta)/2a) et Landscpace par Clouds (-b-sqrt(delta)/2a)
Je print enfin les solutions 

Ligne 67 à 68:
Dernier scénario, Je print: Il n'y a pas de solutions car delta est négatif