# HTML "Canon"

> HTML exercise about ordered lists

* * *

**html-lists-canon** is an educational project, which will be used for HTML courses.

**Note:** the school where the course is given, the [HEPL](http://www.provincedeliege.be/hauteecole) from Liège, Belgium, is a french-speaking school. From this point, the instruction will be in french. Sorry.

* * *

## Exercice sur les listes ordonnées

L’exercice consiste en la réalisation d’une page qui reprend des listes d’appareils photo de marque Canon. Ceux-ci sont regroupés en six catégories listées du niveau le plus expert au moins expert. Dans chaque catégorie, les appareils sont listés dans un ordre de numérotation des appareils de la marque, conformément à ce que vous pouvez voir sur le rendu.

La navigation pourrait utiliser la balise `nav` mais ceci impliquerait de commencer la hiérarchie des titres de la page avec `h2`, avant le premier `h1`. Afin d’avoir le même résultat pour l’accessibilité (identifier la zone comme étant une zone de navigation) sans être obligé de mettre un titre à la navigation, vous pouvez utiliser une `div` dotée d’un attribut `role="navigation"`. Dans la `div` on trouvera une liste de liens sans ordre précis si ce n’est des conventions plutôt habituelles sur le Web. Vous pouvez donc baliser cette liste comme une liste sans ordre.
