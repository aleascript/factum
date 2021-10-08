# A propos du moteur de résolution


## Simplicité 

J'ai voulu créer un moteur simple et réaliste.

On a privilégié la version simple car elle est la plus fluide car chaque champ annonce simplement le nombre de pairs obtenus et le résultat est immédiat.

Les versions initiales faisaient intervenir des dés de chance et parfois un comptage des valeurs des dés.

Ce n'était pas opérationnel.

## Réalisme

J'avais également en tête la simplicité du moteur BRP: une stat sur 100 et on jette un dé, on a le résultat immédiatement. Les joueurs savent à quoi s'en tenir. 

Mais le moteur BRP n'est pas réaliste car dans la vraie vie, on ne connait pas ses statistiques personnelles et il est meme probable qu'elles n'existent tout simplement pas. Le succès et la réussite sont dépendants de pleins d'autres facteurs. 

Quand on analyse un échec ou un succès, on commente en mettant en avant tel ou tel facteur-clé. Il s'avère d'ailleurs qu'il y a souvent plusieurs facteurs pris en compte et que l'on est  incapables de déterminer lequel a été déterminant. 

C'est l'esprit du moteur de Factum: on détermine les facteurs clés et on résout. Tant qu'on n'a pas résolu, on ne peut pas se prononcer. Evidemment plus il y a de facteurs clés dans un camp, plus il a de chance de l'emporter mais ce sont les dés qui en décideront avec un facteur d'incertitude qui, je l'espère, sera stimulant pour les joueurs. 

## Implication

A noter également que les facteurs clés doivent aussi être une source d'inspiration et d'implication des joueurs. 

On peut ne pas être très à l'aise avec le roleplay mais en déterminant les facteurs clés d'une opposition, on commence petit à petit à prendre la mesure de qui l'on est et de l'environnent qu'on a autour. 

Exemples de facteurs-clés possibles originaux: 

- "Par le pouvoir du Crâne ancestral..." : un simple mantra caractérisant un personnage peut être source d'un avantage
- "JJ ne peut pas réussir un plan" : c'est la possibilité d'inclure un facteur hors champ mais synonyme de Destin


## Un jeu narratif guidé par les facteurs

Factum un jeu qui permet de mettre en avant tel ou tel facteurs (issus du jeu ou de la fiction) pour voir ce qui arrive

Le jeu devrait donner ainsi un maximum de pouvoir de liberté aux joueurs.

## Statistiques

Malgré son appartent simplicité, les statistiques apparaissent plutôt riches et intéressantes.

### Statistiques du moteur de résolution

Le moteur a évolué pour avoir des statistiques cohérentes et équilibrées. 

Par exemple, un bug d'une version précédente du moteur était que plus le nombre de dés étaient importants plus les fiascos/exploits l'étaient indépendamment de l'équilibre des forces en présence. La règle pour les fiascos/exploits a donc été revue. 

On n'obtient un fiasco ou un exploit quand le nombre de pairs est strictement supérieur au nombre de pair de l'autre camp. Si l'autre camp n'a aucun pair, le fiasco/exploit est obtenu si la différence est supérieure ou égale à 2. 

Les règles de fortune restent les mêmes: obtention en cas de fiasco sauf si l'on est outsider, dans ce cas, on obtient la fortune en cas d'exploit. 

Ca devrait etre assez simple opérationnellement: 
- on jette les dés (en tenant compte de dés de chance en plus)
- on compte les pairs de chaque côté
- on compare et on obtient le résultat - seul cas à prendre en compte quand la différence de pairs n'est pas zéro, il faut juste vérifier qu'on n'est pas dans un fiasco ou un exploit (ce qui est assez simple: on prend le nombre de pairs du perdant x 2 et si le nombre de pairs du gagnant est strictement supérieur alors on obtient un fiasco ou un exploit - si nombre de pair du perdant = 0, le fiasco aura lieu si le gagnant a 2 pairs ou plus). 

Et voici les stats lissées: 

|Protagoniste|Obstacle|Succes|Echec|-3|-2|-1|+1|+2|+3|Fortunes|Jets|
|---|---|---|---|---|---|---|---|---|---|---|---|
|1D|1D|47|53|4|24|25|18|24|4|4|1,3|
|2D|2D|59|41|11|23|6|24|23|12|11|1,5|
|3D|3D|61|39|15|23|2|24|23|15|15|1,7|
|4D|4D|60|40|15|24|~0|21|24|15|15|1,8|
|5D|5D|60|40|14|26|~0|19|26|14|14|1,8|
|6D|6D|59|41|12|29|~0|18|29|12|12|1,9|
|7D|7D|58|42|11|31|~0|17|31|11|11|1,9|
|8D|8D|58|42|10|32|~0|16|32|10|10|1,9|
|16D|16D|55|45|4|41|N/A|11|41|4|4|2|
|1D|1D|46|54|4|24|25|18|24|4|4|1,3|
|1D|2D|36|64|20|32|12|20|14|2|2|1,4|
|1D|3D|25|75|38|31|6|16|8|1|1|1,5|
|1D|4D|16|84|55|26|3|11|4|~0|~0|1,6|
|1D|5D|10|90|68|21|2|7|2|~0|~0|1,7|
|1D|1D|47|53|4|24|25|18|24|4|4|1,3|
|2D|1D|72|28|2|14|13|20|32|20|2|1,4|
|3D|1D|85|15|1|8|6|16|31|38|1|1,5|
|4D|1D|92|8|~0|4|3|11|26|55|~0|1,6|
|5D|1D|96|4|~0|2|2|7|20|68|~0|1,7|
|1D|2D|35|65|20|32|12|20|14|2|2|1,4|
|2D|3D|45|55|24|28|3|23|16|7|7|1,6|
|3D|4D|47|53|24|28|~0|21|17|9|9|1,7|
|4D|5D|48|52|22|30|~0|20|20|9|9|1,8|
|7D|8D|49|51|15|36|~0|16|26|7|7|1,9|
|2D|1D|72|28|2|14|13|19|32|20|2|1,4|
|3D|2D|74|26|7|16|3|23|28|24|7|1,6|
|4D|3D|73|27|9|17|~0|21|28|24|9|1,7|
|5D|4D|71|29|9|20|~0|20|30|22|9|1,8|
|8D|7D|67|33|7|26|~0|16|36|15|7|1,9|
|1D|3D|25|75|38|31|6|16|8|1|1|1,5|
|2D|4D|32|68|37|29|2|18|10|4|4|1,7|
|3D|5D|35|65|34|30|~0|18|13|5|5|1,8|
|4D|6D|37|63|29|33|~0|17|15|5|5|1,8|
|7D|9D|40|60|19|41|~0|14|21|4|4|1,9|
|3D|1D|85|15|1|8|6|16|31|38|1|1,5|
|4D|2D|84|16|4|10|2|18|29|37|4|1,7|
|5D|3D|82|18|5|13|~0|18|30|34|5|1,8|
|6D|4D|79|21|5|15|~0|17|33|29|5|1,8|
|9D|7D|74|26|4|21|~0|14|41|19|4|1,9|
|1D|4D|16|84|55|26|3|11|4|~0|~0|1,6|
|2D|5D|22|78|49|27|~0|14|7|2|2|1,7|
|3D|6D|26|74|43|31|~0|14|9|3|3|1,8|
|4D|7D|28|72|37|35|~0|14|11|3|3|1,9|
|7D|10D|32|68|24|44|~0|12|17|3|3|2|
|4D|1D|92|8|~0|4|3|11|26|55|~0|1,6|
|5D|2D|90|10|2|7|~0|14|28|49|2|1,7|
|6D|3D|88|12|3|9|~0|14|31|43|3|1,8|
|7D|4D|86|14|3|11|~0|14|35|37|3|1,9|
|10D|7D|80|20|3|17|~0|12|44|24|3|2|


Il y a un léger avantage pour les protagonistes mais c'est assumé car ce sont eux les héros de l'histoire.

La possibilité d'obtenir des fortunes augmentent plus il y a de dés dans les pools et cela reflète bien que c'est la complexité qui est pourvoyeuse d'expérience.
 

### Moteur sans relance sur 6

On aurait pu envisager également de ne pas relancer en cas de 6. 

Le fait de ne plus avoir de dés de chance permet par ailleurs d'utiliser n'importe quel dé (D6, D10, D20...) puisque seule la parité importe.

A chacun ses dés fétiches donc.

Par contre, cela fige un peu plus les statistiques. En particulier, il devient impossible de réaliser un fiasco/exploit sur une opposition 1/1. Et de manière générale, quand un camp n'a un seul dé, il lui est impossible de réaliser un exploit ou un fiasco. Mais cela peut être assumé pour pousser les joueurs à poser plus d'un dé. 


|Protagoniste|Obstacle|Succes|Echec|-3|-2|-1|+1|+2|+3|Fortunes|Jets|
|---|---|---|---|---|---|---|---|---|---|---|---|
|1D|1D|50|50|N/A|25|25|25|25|N/A|N/A|1|
|2D|2D|62|38|6|25|6|31|25|6|6|1|
|3D|3D|64|36|11|23|2|30|23|11|11|1|
|4D|4D|63|37|12|24|~0|27|24|12|12|1|
|5D|5D|62|38|11|26|~0|24|26|11|11|1|
|6D|6D|61|39|10|29|~0|23|29|10|10|1|
|7D|7D|60|40|9|31|~0|21|31|9|9|1|
|8D|8D|60|40|8|32|~0|20|32|8|8|1|
|16D|16D|57|43|3|40|N/A|14|40|3|3|1|
|1D|1D|50|50|N/A|25|25|25|25|N/A|N/A|1|
|1D|2D|37|63|12|38|13|25|12|N/A|N/A|1|
|1D|3D|25|75|31|38|6|19|6|N/A|N/A|1|
|1D|4D|16|84|50|31|3|13|3|N/A|N/A|1|
|1D|5D|9|91|66|23|2|8|2|N/A|N/A|1|
|1D|1D|50|50|N/A|25|25|25|25|N/A|N/A|1|
|2D|1D|75|25|N/A|13|12|25|38|13|N/A|1|
|3D|1D|87|13|N/A|6|6|19|38|31|N/A|1|
|4D|1D|94|6|N/A|3|3|13|31|50|N/A|1|
|5D|1D|97|3|N/A|2|2|8|23|65|N/A|1|
|1D|2D|37|63|13|37|13|25|13|N/A|N/A|1|
|2D|3D|47|53|19|31|3|28|16|3|3|1|
|3D|4D|49|51|20|30|~0|27|16|6|6|1|
|4D|5D|50|50|19|31|~0|24|18|7|7|1|
|7D|8D|50|50|12|38|~0|20|25|5|5|1|
|2D|1D|75|25|N/A|12|13|25|37|13|N/A|1|
|3D|2D|78|22|3|16|3|28|31|19|3|1|
|4D|3D|77|23|6|16|~0|27|30|20|6|1|
|5D|4D|74|26|7|18|~0|24|31|19|7|1|
|8D|7D|70|30|5|25|~0|20|38|12|5|1|
|1D|3D|25|75|31|37|6|19|6|N/A|N/A|1|
|2D|4D|33|67|33|33|2|22|9|2|2|1|
|3D|5D|36|64|30|34|~0|21|11|3|3|1|
|4D|6D|38|62|26|36|~0|20|13|4|4|1|
|7D|9D|40|60|16|43|~0|17|19|3|3|1|
|3D|1D|88|12|N/A|6|6|19|37|31|N/A|1|
|4D|2D|88|12|2|9|2|22|33|33|2|1|
|5D|3D|85|15|3|11|~0|22|34|30|3|1|
|6D|4D|83|17|4|13|~0|20|36|26|4|1|
|9D|7D|77|23|3|19|~0|17|43|16|3|1|
|1D|4D|16|84|50|31|3|13|3|N/A|N/A|1|
|2D|5D|22|78|46|31|~0|16|5|~0|~0|1|
|3D|6D|25|75|40|35|~0|16|7|2|2|1|
|4D|7D|27|73|34|39|~0|16|9|2|2|1|
|7D|10D|31|69|21|47|~0|15|15|2|2|1|
|4D|1D|94|6|N/A|3|3|13|31|50|N/A|1|
|5D|2D|93|7|~0|5|~0|16|31|46|~0|1|
|6D|3D|91|9|2|7|~0|16|35|40|2|1|
|7D|4D|89|11|2|9|~0|16|39|34|2|1|
|10D|7D|83|17|2|15|~0|15|47|21|2|1|

### Moteur sans limite de relance

Dans cette version on relance autant de fois qu'un 6 sort. En pratique quand les pools sont importants, on se retrouve à relancer trop de fois.

|Protagoniste|Obstacle|Succes|Echec|-3|-2|-1|+1|+2|+3|Fortunes|Jets|
|---|---|---|---|---|---|---|---|---|---|---|---|
|1D|1D|47|53|5|24|25|18|24|5|5|1,4|
|2D|2D|59|41|12|23|6|24|23|12|12|1,6|
|3D|3D|61|39|16|22|2|23|22|16|16|1,9|
|4D|4D|60|40|16|24|~0|21|24|16|16|2|
|5D|5D|59|41|15|26|~0|19|26|15|15|2,1|
|6D|6D|58|42|13|28|~0|17|28|13|13|2,2|
|7D|7D|58|42|12|30|~0|16|30|12|12|2,3|
|8D|8D|57|43|11|32|~0|15|32|11|11|2,4|
|16D|16D|55|45|5|40|N/A|10|40|5|5|2,8|
|1D|1D|47|53|5|24|25|18|24|5|5|1,4|
|1D|2D|35|65|20|32|13|19|14|3|3|1,5|
|1D|3D|25|75|39|30|6|15|8|1|1|1,6|
|1D|4D|16|84|55|26|3|11|4|~0|~0|1,8|
|1D|5D|10|90|68|20|2|7|3|~0|~0|1,9|
|1D|1D|46|54|5|24|25|18|24|5|5|1,4|
|2D|1D|71|29|3|14|12|19|32|20|3|1,5|
|3D|1D|84|16|1|8|6|15|30|39|1|1,6|
|4D|1D|92|8|~0|5|3|11|25|55|~0|1,8|
|5D|1D|95|5|~0|3|2|7|20|68|~0|1,9|
|1D|2D|36|64|20|32|12|19|14|3|3|1,5|
|2D|3D|45|55|25|27|3|22|16|7|7|1,8|
|3D|4D|47|53|25|27|~0|21|17|9|9|1,9|
|4D|5D|48|52|23|29|~0|19|20|10|10|2,1|
|7D|8D|49|51|16|35|~0|15|26|8|8|2,4|
|2D|1D|71|29|3|14|13|19|32|20|3|1,5|
|3D|2D|74|26|7|16|3|22|27|25|7|1,8|
|4D|3D|72|28|9|17|~0|21|27|25|9|1,9|
|5D|4D|70|30|10|20|~0|19|29|23|10|2,1|
|8D|7D|66|34|8|26|~0|15|36|16|8|2,4|
|1D|3D|25|75|39|30|6|15|8|1|1|1,6|
|2D|4D|33|67|38|28|2|18|11|4|4|1,9|
|3D|5D|36|64|35|29|~0|17|13|6|6|2|
|4D|6D|37|63|30|32|~0|16|15|6|6|2,1|
|7D|9D|40|60|20|40|~0|13|22|5|5|2,4|
|3D|1D|84|16|1|8|6|15|30|39|1|1,6|
|4D|2D|84|16|4|11|2|18|28|38|4|1,9|
|5D|3D|81|19|6|13|~0|17|29|35|6|2|
|6D|4D|79|21|6|15|~0|16|32|30|6|2,1|
|9D|7D|73|27|5|22|~0|13|40|20|5|2,4|
|1D|4D|16|84|55|26|3|11|4|~0|~0|1,8|
|2D|5D|23|77|50|26|~0|13|7|2|2|1,9|
|3D|6D|26|74|44|30|~0|13|9|3|3|2,1|
|4D|7D|28|72|38|34|~0|13|12|4|4|2,2|
|7D|10D|32|68|25|42|~0|12|18|3|3|2,4|
|4D|1D|92|8|~0|4|3|11|26|55|~0|1,8|
|5D|2D|90|10|2|7|~0|13|26|50|2|1,9|
|6D|3D|87|13|3|9|~0|13|30|44|3|2,1|
|7D|4D|85|15|4|12|~0|13|34|38|4|2,2|
|10D|7D|79|21|3|18|~0|12|42|25|3|2,4|

## Quand un protagoniste ou un obstacle n'a aucun trait ? 

Dans tout test, il y a des facteurs contre à prendre en compte et donc tous les tests sont des oppositions. C'est le choix de HeroQuest et il me parait tout a fait acceptable. S'il n'y a aucun facteur contre, il n'y a pas lieu de réaliser le test et le résultat est automatique. 

## Probable/Improbable

* Les -/+3 (Fiasco/Exploit) sont de l'ordre de l'improbable, de la surprise
* Les -/+2 (Echec/Succes) sont de l'ordre du plus évident.
* Les -/+1 (Echec/Succes partiels) sont entre les deux. Ils peuvent faire surgir le plus évident mais aussi faire intervenir quelque chose d'improbable. Ce qui caractérise le plus les -/+1 c'est le côté irrésolu, incomplet, partiel de la résolution.

Note: ce qui est notable c'est qu'a nouveau le pair (+/-2) apparait comme facteur prépondérant alors que l'impair (+/-1, +/-3) apparaissent plutot comme des facteurs rares, important a posteriori mais négligeables a priori.


## Quand faire des jets ? 

La question se pose d'autant plus que le jeu permet de faire des jets sur à peu près n'importe quoi. Il s'agit donc bien du canon du jeu dont il est question mais aussi d'une façon de savoir quand et pourquoi on jette les dés. 

En particulier, le mode solo est a priori différent du mode groupe car par nature, le mode solo invite à plus de jets de dés pour faire émerger l'histoire. 

Cette question traite aussi de la précédence. Le jet précède-t'il le récit ou est-ce l'inverse ? Cela dépend du récit en cours. Dans un récit très immersif, ca sera le récit qui précédera le jet mais sinon dans la plupart des cas, on fera des jets avant le récit pour savoir de quoi il retourne et lancer le récit en quelque sorte. 

## Jets derrière l'écran

Possibilité ou pas d'introduire le fait que la Destinée jette des dés pour les protagonistes derrière l'écran.

## Revue des situations types 

Les interprétations dépendent grandement du style de jeu. Un jeu préparé avec un scénario aura des réponses déjà prêtes en fonction du scénario. Par contre, un récit au fil de l'eau, générera des réponses improvisées. 


### Soin

Les héros tentent de soigner un autre héros. Un héros peut également tenter de s'auto-soigner. Les héros peuvent aussi n'avoir aucune compétence de soin et faire appel à un tiers. 

Quand le soin fonctionne on pourra alors diminuer la jauge concernée. 

* Fiasco: la blessure empire. Attention, cela pourrait éliminer un personnage. Or si ce n'est pas encore son heure, il faut trouver une autre interprétation. Dans tous les cas, le soin n'a pas marché. Plusieurs pistes: le héros s'évanouit / Le personnage qui essayait de les soigner n'est qu'un escroc et va chercher à les duper, voler / On fait avancer une menace ou on introduit un danger : pendant que vous tentez de soigner machin, un bruit aux alentours se fait entendre. Vous n'êtes pas seuls apparemment ! / ...

* Echec: le soin n'a pas marché. 

* Echec partiel: le soin n'a pas marché mais une opportunité s'ouvre. Exemples: si les héros trouvent tel ou tel ingrédient alors le soin sera possible (avec avantage en plus cette fois) / le soin ne marche pas mais le héros découvre une puce qu'on lui implanté à son insu / ...

* Succès partiel: le soin a marché (on peut donc diminuer la jauge concernée) mais il y a des effets secondaires / il faut se reposer 1 journée, 1 semaine sinon la blessure va se réouvrir / le soignant demande le double de ce qu'il avait annoncé / le soignant dénonce les héros aux autorités / ...

* Succès: le soin a marché. 

* Exploit: le soin a marché. Possibilité de diminuer 2 traits de jauge / Le soignant peut donner quelque chose aux héros (potion, implant, etc...) / Le héros peut découvrir une plante particulièrement rare qu'il peut garder pour une prochaine fois / ...

### Résister à 

En gros il s'agit de réagir à une attaque extérieure et le jet n'est là que pour interpréter les résultats. 

Opérationnellement: 
- déterminer l'objectif de l'attaque (qui sera donc appliqué en cas d'échec)

* Fiasco: on subit l'objectif de l'attaque avec quelque chose de négatif en plus:  perte de jauge mais aussi évanouissement / etre fait prisonnier / etre séparé / succomber a ses pulsions mais de maniere totalement amplifiée / obtention d'un trait allergie, sensibilité à ...  

* Echec: on subit l'objectif de l'attaquant 

* Echec partiel: on prend tout pour soi et les autres sont saufs / on arrive a temporiser pour les autres / on ne résiste pas mais on est immunisé / ...

* Succès partiel: on résiste mais il y a des effets secondaires (trait allergie, sensibilité à ...) / on résiste mais il faudra refaire un jet plus tard / ...

* Succès: on résiste 

* Exploit: on résiste et on est immunisé 

### Perception 

Il est important de demander au personnage qui cherche ce qu'il cherche avant de jeter le dé. Cela permet d'établir la difficulté du jet: plausibilité, dissimulation de l'information qu'on cherche, facteurs extérieurs qui peuvent gêner ou aider la recherche, etc...

Une particularité de la perception c'est également de savoir si l'on jette les dés devant le héros ou pas. 

L'option jet caché est intéressante car cela ouvre des possibilités de doute. Pour autant cela n'est pas la panacée non plus. En effet, un héros qui n'a eu que des impairs mettra plus volontiers en doute l'information car il se doutera bien qu'il n'a pas réussi. 

Opérationnellement: 
- réponse improvisée ou cadrée ? 
- jet caché ou ouvert ? 

Le mode opératoire est important car il impacte les interprétations. 

* Fiasco: 
    - déterministe: aucune info / l'objet de la recherche se rend compte qu'on l'observe et le prend mal / avancée d'une menace, introduction d'un danger / l'objet qu'on observe est détruit ou en cours de l'être / ...
    - impro: comme au dessus mais aussi une info douloureuse à connaitre est révélée / révélation du pire 

* Echec: 
    - déterministe: aucune info 
    - impro: comme au dessus mais aussi révélation de quelque chose de désagréable. On obtient l'infirmation de ce qu'on cherchait. Si l'on veut savoir que quelqu'un est digne de confiance, on découvrira que non donc. Et dans le cas d'un fiasco, il pourra meme se révéler un traitre. Si le jet a été caché, la destinée pourra ne donnait aucune info mais exploiter ce nouvel aspect révélé par les dés pour ce personnage.  
    
* Echec partiel: on ne remarque rien sur ce qu'on cherchait mais on remarque quelque chose d'autre / on se dit qu'en faisant telle ou telle chose on aura une meilleure perception (exemple: monter sur la statue pour mieux voir, aller voir un tel, etc...)

* Succès partiel: on obtient l'info mais elle n'est pas tout à fait celle qu'on souhaitait / on sait qu'on sait meme si le résultat de l'info n'est pas celle qu'on voulait entendre (style impro avec jet caché) on obtient l'info mais on a été remarqué / on obtient l'info mais on a laissé des traces / on obtient l'info mais on a cassé quelque chose / ...

* Succès: on obtient l'info. Dans le cas d'un style impro, on obtient la confirmation de ce qu'on cherchait et plutôt quelque chose de positif pour soi. Exemple: si l'on cherche si untel est honnête ou pas, on obtiendra qu'il l'est. 

* Exploit: on obtient l'info et on en est sûr. Dans le cas d'un style impro, on obtient la confirmation de ce qu'on cherchait et plutôt quelque chose d'exceptionnement positif pour soi. Exemple: si l'on cherche si untel est honnête ou pas, on obtiendra que non seulement il l'est mais qu'en plus il est un allié.  

### Fabriquer 

### Combat

### Cas du combat à distance 

### Se préparer 

### Convaincre, charmer, manipuler 

### Eviter 

### Désamorcer un piège 

### Course poursuite 

### Lutter contre les éléments


# Character building

## Révéler les protagonistes

Il y a des éléments nécessaires pré-établis à la création des protagonistes mais l'idée du  jeu est de permettre ensuite aux Protagonistes de se révéler petit à petit en cours de partie, surtout pendant la session zéro. Le problème n'est pas simple car il faut arbitrer les deux questions suivantes: 

* Par quoi commencer ? C'est à dire quels sont les éléments nécessaires ? C'est à la Destinée de fournir ce cadre à mon avis quand il crée le jeu. 
* Où s'arrêter ? C'est à dire quand estime-t'on qu'on ne peut plus révéler de traits (hormis via les Fortunes)  ? La question est là plus délicate. 

**Piste avec les fortunes**

On pourrait avoir un certain nombre de fortunes qui ne peuvent être utilisée que pour révéler le protagoniste dans les premières sessions. 

Mais cela pose alors deux questions: 

1. Quel nombre attribuer en début de partie ? 
2. A quel moment bascule-t'on sur le mode fortune qui permet de modifier un résultat et de demander un rebondissement positif à la Destinée ? 

**Piste avec un pool de révélations** 

La Destinée pourrait construire son jeu en définissant un nombre de révélations possibles après la création du protagoniste pour permettre pendant le jeu de révéler des traits (non implicites) en dehors du mécanisme des Fortunes qui lui prendrait ensuite le relais une fois les révélations épuisées.  

**Réponse simplifiée**

C'est en fait probablement plus simple que cela. Un fiasco est l'occasion de révéler un défaut ou une faiblesse pour le protagoniste et inversement un exploit est l'occasion de révéler un trait fort du personnage. Et donc les choses se font naturellement. 

# Création du jeu 

Une idée commence à émerger: **jouer pour créer le jeu**

Cela permettrait à la Destinée de tester son jeu en quelque sorte (en mode solo). 

Faire des allers retours entre les étapes suivantes: 

* A. Poser le cadre de l'univers 
* B. Créer un protagoniste adversaire: essayer de prendre un profil proche des protagonistes (en étant un adversaire potentiel)
* C. Lister les scènes types du jeu 
* D. Jouer les scènes types (en dehors de toute intrigue) en impliquant l'adversaire.
* E. Intégrer un groupe type 

L'idée est d'enrichir l'univers et les éléments du jeu tout en jouant. 

Note: a priori, on joue sans prendre en compte le Destin. 

## Une pierre, deux coups

L'idée sous-jacente est de voir s'il est possible d'avoir un mode solo qui soit générateur de ressources pour inviter ensuite des amis et jouer à plusieurs. 

Cela implique une écriture particulière qui relève plus du listing que du style. 

Comparez par exemple: 

```
Vous faites face à la forêt hantée. 
Devant vous, un mur vert qui s'étend à l'infini apparemment. 
Des arbres à perte de vue et derrière vous voyez pas plus loin 
que quelques dizaines de pas. 
Aucun chemin ne semble présent. 
Il semble y faire sombre. 
```

```
FORET HANTEE
Immense
Visibilité réduite 
Sombre
Pas de chemin
```

Autre exemple sur une une ligne: en mettant en gras ce qui pourrait servir dans une résolution.  

* **LA MERE SUPERIEURE**: **Très âgée**, **Canne**, Courbée, Visage creusé, Des yeux pétillants d'**intelligence**, Une robe de soeur couleur sombre, Un air **revêche** et dur, Des grosses **bagues** brillantes aux doigts 

On obtient donc des ressources directement exploitables. Reste plus qu'a assembler le pseudo-récit en assemblant les éléments dans des scènes types à jouer ce qui permettra de faire émerger des traits pour nos ressources. 

Exemple:

```
SITUATION: putsch de Ralandis 
LIEU: le hall du chef 
CONTEXTE: l'ancien chef vient de mourir
DETAILS: 
    - Ambiance lugubre
    - Des chants de femmes
    - Une lumière tamisée
    - Tous les gens importants du clan sont là (le Cercle Extérieur)
    - Le corps de RIALTAR git sur un chariot mortuaire ouvragé et décoré 
PERSONNAGES: 
    - RALANDIS: veut devenir le nouveau chef 
    - KAILLA: refuse qu'un Uroxi devienne chef
    - BOURDABAR: veut manger le chef mort ! 
    - CRIMOS: veut faire le choix le plus juste aux yeux de Lankhor Mhy 
    - ... 
CONFLIT: chacun s'exprime mais c'est le Conseil (le Cercle interne) qui vote.
D'un coté les avantages de Ralandis (lui meme et ceux acquis a sa cause) contre ceux qui ne veulent pas de lui. 
Le jet permettra de savoir si des indécis l'ont choisi ou pas. 
Exemple: echec partiel -> le conseil demande à Ralandis de faire ses preuves 
avant le jour divin de la prochaine semaine de la Vérité 
(dans 2 semaines donc!) 
Il doit venger RIALTAR et apaiser les Dieux. 
Le problème pour lui c'est que ce faisant 
il devra se détourner de ses obligations de lutte contre le Chaos 
(conflit au sein des Uroxi, devra choisir entre combattre 
un ennemi chaotique ou remplir sa quête 
et s'éloigner de l'eternelle bataille...).  
```

Rien n'empêche dans un pur bullet-style de détailler chaque élément important ce qui permet finalement d'adapter la scène pour d'autres joueurs. Par exemple, la mort du chef de clan mais sans le putsch de Ralandis. 

On pourrait ainsi rentrer de plain-pied dans le setting en jouant des résolutions avec de vrais traits et en rôdant ainsi sa façon d'appréhender les conséquences des jets. 

On peut également faire l'exercice avec des ressources existantes pour transcrire au format Factum des descriptions, statistiques d'autres moteurs de jeu. L'idée est d'avoir une fiche de lieu, de second rôle directement exploitable par la suite. 

Reste maintenant à définir aussi une organisation de classement pour pouvoir s'y retrouver facilement.  

## Un gameplay proche du jeu de société 

Une autre piste de recherche est celle des cartes. 

Préparer des cartes et les révéler au fil du jeu. 

# Les modes de jeu  

J'ai tenté de me départir des réflexes acquis par des années de jeux de rôles. 

Et c'est donc pour cela que j'ai voulu inclure différents modes de jeu pour sortir du modèle classique (MJ/PJ). Pour l'instant je sèche encore sur l'ambivalence du mot rôle dans jeu de rôles. 

En effet, de manière courante, on entend par rôle, le roleplay, la capacité à incarner le rôle d'un personnage (un PJ ou un PNJ) mais d'un autre côté le rôle peut également désigner le rôle du joueur au sein du jeu: est-il meneur ou joueur ? Et cette ambivalence est d'autant plus présente quand on commence à travailler sur les différents modes: le joueur est-il le Chaos en charge des menaces sur les Héros, ou est-il un héros, ou encore est-il le Cosmos en charge de donner vie au monde ? Mais si l'on va meme plus loin, son rôle pourrait être DJ, spectateur, régisseur ? (voir tous les rôles de Cosmos?)

A creuser:
* Cosmos incarne le destin en tant que garant du monde mais aussi le hasard en tant que révélateur du monde. Le monde étant suffisamment complexe pour que tout ne puisse etre défini par avance. 
* Chaos incarne le destin en tant que garant de l'intrigue et n'utilise par le hasard car il s'appuie pour cela sur Cosmos. C'est pour cela que les jets d'Oracle sont réalisés pour Cosmos. 

# Organisation des ressources

J'ai du mal à me satisfaire d'une organisation statique. J'ai donc tenté de simplifier en identifiant 2 types de ressources: 

* les questions 
* les lexiques 

C'est aussi simple que cela. 

Cela a comme avantage, qu'on peut modifier, étendre le jeu très facilement en créant, modifiant des questions et des lexiques propres à l'ambiance qu'on veut créer. 

## Les lexiques en tant qu'Oracles 

Par définition, un lexique étant une liste d'éléments ayant le même thème, il peut tout à fait servir d'Oracle. 

Mais je n'ai pas encore trouvé un moyen simple de pouvoir tirer au sort un élément dans une liste quelconque. 

Quelques pistes: 

- quand la liste est courte et paire, on peut utiliser un dé. (3 avec un D6)
- quand la liste est longue mais pas trop, on peut utiliser des cartes classiques
- on peut également répartir par dichotomie et lancer plusieurs dés mais cela nécessite une mise en place pour être utilisée
- utiliser les milliseconds pour obtenir un nombre correspondant à ce qu'on cherche mais cela pose un probleme car on est en base 10. (exemple d'une liste à 12 -> il faut donc un résultat à 2 chiffres et on va donc rejeter un tas de résultats (>12) avant d'arriver au bon résultat)
- utiliser une appli de génération de nombres aléatoires (ca repond au probleme mais assez fastidieux et trop technologique)


Bref, c'est le probleme du moment mais je doute de pouvoir trouver un algo naturel (dés, cartes, ...) facile à utiliser. 

Apres, on peut aussi dire qu'il y a: 

* des lexiques clairement orientés Oracle et présentés avec leur table de correspondance (distance, directions symboliques, intrigues)
* des lexiques orientés inspiration et présentés sous forme de liste (avec toujours la possibilité de les utiliser en Oracle moyennant une application)

Lexique compact: présenter les lexiques avec des numéros (soit a la ligne mais aussi en liste pour etre plus compact mais moins lisible pour le coup)

1. borné 2. accueillant 3. grognon 4. renfrogné 5. bourru  6. jovial 7. accablé

Lexique développé: 

1. borné 
2. accueillant 
3. grognon 
4. renfrogné 
5. bourru  
6. jovial 
7. accablé

# Storytelling 

L'idée du  jeu est aussi de fournir tous les outils pour pouvoir inventer collectivement une histoire. 

Le moteur de résolution est essentiel mais ne fait pas tout. 

Il nous faut donc nous pencher sur d'autres outils. 

En particulier l'objectif est aussi de pouvoir inventer facilement des histoires crédibles de façon improvisée. C'est tout l'objet du mode tresse qui enlève de la responsabilité au MJ classique pour faciliter l'improvisation. 

Mais qu'est ce que l'improvisation ? 

Déjà il faut être lucide et garder en tête qu'il y aura toujours une étape de préparation. Mais le but est de réduire la durée de cette dernière voire même idéalement de rendre celle-ci ludique. 

Il nous faut donc étudier les techniques d'impro et voir comment les rendre disponibles pour le jeu. 

## La méthode des 5 "pourquoi" et du "et si"

Quand on prépare un élément d'intrigue, se poser au moins 5 pourquoi (ce qui permet de préparer le questionnement qu'auront les protagonistes). 

Utiliser également le "et si" pour envisager d'autres embranchements possibles. 

## Les éléments d'une bonne intrigue

https://www.aproposdecriture.com/8-etapes-essentielles-pour-contruire-une-bonne-intrigue

1. Le but ~ le pitch de l'intrigue 
2. La conséquence ~ la catastrophe imminente d'une menace 
3.  Les conditions ~ des jalons (les enjeux?)
4. Les avertissements ~ les étapes d'une menace 
5. Les coûts ~ les pertes dans les oppositions
6. Les dividendes ~ les gains dans les oppositions 
7. Les prérequis ~ pas d'équivalent (les scènes ?)
8. Les conditions préalables ~ pas d'équivalent (les défis personnels?)

Ce qui est intéressant c'est qu'on voit qu'on retrouve dans ces conseils les éléments modernes du JdR. 
Ce n'est pas forcément opérationnel mais ca peut etre une base de travail. 

## Les déclencheurs 

L'élément déclencheur est un concept de dramaturgie qui a été adapté de maniere indirecte en PbtA. 

En gros, il y a des éléments de l'histoire qui ont un impact important sur l'histoire. 

Mais l'échelle est importante. Tous les éléments n'auront pas un impact important. 

Idée: seuls les fiascos ou les exploits peuvent vraiment changer l'histoire quelque soit l'échelle. 