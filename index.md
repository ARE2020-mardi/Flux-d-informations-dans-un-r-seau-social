# Résumé

La propagation des informations dans les réseaux sociaux, tels que Facebook ou Instagram ou encore Twitter, est un domaine assez complexe qui est composé de plusieurs paramètres qui varient d’un réseau a l’autre. 
Comme vous pouvez le savoir, ce thème est d’une importance cruciale dans notre monde car de nos jours, les réseaux sociaux occupent une place importante voir indispensable, les consulter  est devenu la routine à la majorité d’entre nous.
Notre projet de recherche permet de mieux identifier la manière dont l’information  se propage et par quel moyen cette propagation devient très rapidement exponentielle déclanchant ainsi le «Buzz». 
Cette propagation sera étudiée de façon généraliste, c’est-à-dire qu’elle sera composée de plusieurs paramètres qui sont ceux qui la font varier de manière visible et concrète (Goûts, réactions, partages...etc), ce qui nous permettra d’anticiper sur les effets d’une information sur une communauté d’internautes selon les critères auxquels elle répond parmi ceux annoncés précédemment.
C’est avec une modélisation numérique qu’il a été possible d’avoir une approche du phénomène.

## Information Flow in a Social Network

Spreading information on social networks, such as Facebook or Instagram or Twitter, is a rather complex area that is composed of several parameters that vary from one network to another.
As you may know, this theme is of crucial importance in our world because nowadays, social networks occupy an important place and are indispensable, consulting them became routine to the majority of us.
Our research project helps to better identify how information spreads and how this propagation becomes very rapidly exponential thus triggering the «Buzz».
This spread will be studied in a general way, that is to say, it will be composed of several parameters that are those that make it vary in a visible and concrete way(likes,reactions, shares...etc),which will allow us to anticipate the effects of information on a community of Internet users according to the criteria it meets among those announced previously.
It is with numerical modelling that it was possible to have an approach to the phenomenon.

## Présentation de l'équipe

|(´・ω・｀)| ( ͡° ͜ʖ ͡°) | ಠ_ಠ | ᕕ( ᐛ )ᕗ |
|-----|--|--|--|
| BENCHIKH.Yasser | LAOUAJ.Hicham | LELOUCHE.Elie  | MURAT.Kévin  |


## Description synthétique du projet

**Problématique :** 

Quels sont les paramètres influant sur l'ampleur de la propagation des flux d’information dans les réseaux sociaux?

**Hypothèse principale :** 

Nous avons tout d’abord émis l’analyse suivante : il existe deux états dans le partage de l’information : l’information partagée et le public qui la partage. Nous avons donc essayé de chercher dans ces deux états quels paramètres pouvaient influer sur la propagation d’une information dans les réseaux sociaux.

**Hypothèses secondaires :**
 
Les relations entre personnes: plus les gens ont des liens étroits d'amitié plus l'information va se propager rapidement.

La crédibilité de l'information: plus elle est élevée, plus sa circulation est large et rapide.        

Le temps que dure la propagation: plus elle est importante plus sa propagation dure longtemps (ex: Coronavirus).

**Objectifs :** 

Comprendre l'influence de certains paramètre sur la propagation d'une information en les faisant varier lors de la modélisation.

**Critère(s) d'évaluation :**
 
Nous avons alors d’abord cherché autour de l’objet partagé : sa nature (pub, information géopolitique ou bien simple vidéo décrivant le quotidien d’une personne lambda et bien d’autres…), la vitesse de propagation de l’information etc...
Mais aussi autour des personnes concernées : leur jugement sur la crédibilité de l’information, le nombre d’amis  etc...

## Présentation structurée des résultats

C’est avec une modélisation numérique qu’il a été possible d’avoir une approche du phénomène. 
Pour cela, nous avons donc écrit un programme Python dans lequel seuls quelques uns des paramètres sités précédemment ont été choisis dans la modélisation informatique car il a été considéré qu’ils étaient les plus influents à savoir : la crédibilité de l’information, le nombre d’amis maximum qu’un acteur du partage peut avoir, mais aussi la vitesse de propagation de l’information concernée.

### 1. La crédibilté:

Comme nous le savons tous, le phénomène de la désinformation s’est développé avec la grande aide des réseaux sociaux.

S’est ainsi développé une méfiance quant à la véracité des propos émis au sein des réseaux sociaux qui, bien évidemment, constituera l’objet d’un réel test de validation afin de décider sur l’intérêt de son partage ou bien même du potentiel danger qu’il peut représenter.

Dans la modélisation informatique élaborée, l’utilisateur du programme pourra régler un curseur et décider du seuil de crédibilité au-delà duquel l’information pourra être considérée comme étant crédible. 
Ainsi chaque boule ou sphère représentant un individu deviendra bleue si l’information a été jugée crédible ou non et si la personne a jugé bon de la partager ou non.
Ce jugement représente en fait un des premiers critères influant sur le partage de l’information car permettant de juger l’intérêt d’un quelconque partage.

### 2. Le nombre d’amis:

Un autre phénomène est apparu et s’est développé avec les réseaux sociaux : la   notion d’ « amis » virtuels. 
En effet il se peut qu’une personne ait 1000 amis alors qu’elle n’en connait qu’un seul !

Ainsi il parait donc évident qu’avec cette conception de l’amitié une personne partagera l’information a un nombre plus important d’amis si elle en a plus .

Ce facteur jouera donc un rôle dans la vitesse de propagation de l’information.
Dans la modélisation élaborée le nombre d’amis sera représenté par l’apparition de plusieurs liens entre différents nœuds.
L’utilisateur de la modélisation pourra alors choisir à l’aide d’un curseur le nombre d’amis maximum pouvant être possédé par une personne quelconque.
Ainsi plus la barre est haute plus la chance qu’une personne ait un nombre important d’amis sera importante et la vitesse de propagation de l’information augmentera.

### 3. La vitesse de propagation de l’information:

Dans le point précédent il a été question de parler du nombre d’amis, facteur important dans la vitesse de propagation de l’information.
Cependant la vitesse de propagation ne dépend pas uniquement bien que grandement du nombre d’amis d’une personne il a paru donc judicieux de prendre un compte un troisième paramètre regroupant tous les autres facteurs influant sur la vitesse de propagation de l’information afin de rendre un peu plus réaliste la modélisation.

Pour prendre en compte ce paramètre il suffira de régler un curseur pour choisir une valeur de 1 à 10 qui décidera de même de la vitesse de propagation de l’information.

### 4. Un environnement idéal:

Au départ de la présentation il a été question de parler de la crédibilité d’une information en présentant ce paramètre comme étant uniquement relatif à la nature de l’information et non pas à la personne recevant l’information.

Cependant ca n’est pas totalement vraie pour une même information il peut y avoir deux avis différent concernant la crédibilité. Il suffit simplement de voir la polémique que provoque le débat sur l’existence du réchauffement climatique : la controverse existe dans tous les sujets possibles, même si cette dernière quelques fois n’a aucun sens, il se peut que l’homme contredise pour…. Contredire, simplement.

C’est pour ceci qu’il a paru judicieux pour la simplicité du programme et de la modélisation de faire un seul tirage pseudo-aléatoire de la valeur de crédibilité afin d’obtenir une linéarité et ne pas forcer l’appareil à refaire le tirage aléatoire pour chaque personne.

Bon essai !

## Lien vers page de blog : <a href="https://are2020-mardi.github.io/Flux-d-informations-dans-un-reseau-social"> C'est ici ! </a>

## Bibliographie :

**Carte mentale de vos mots-clés, en utilisant** <a href="https://framindmap.org/mindmaps/index.html">Framindmap </a> 




Liste de l'ensemble des ressources bibliographiques utilisées pour vos travaux. 

[1] Xiaolan Sha. Personalizing trending content in social media. Sociology.  Télécom ParisTech, 2013. English. Disponible sur : https://pastel.archives-ouvertes.fr/tel-01226534.
                                                                                                           
[2] Dominique DELISLE, « TÉLÉCOMMUNICATIONS - Transfert d'information par paquets dans les réseaux », Encyclopædia Universalis [en ligne]. Disponible sur: https://www.universalis.fr/encyclopedie/telecommunications-informatique-et-telecommunications/.
                                                                                                                           
[3] Alexandra Patard, «Instagram: étude sur les tendances de l’engagement», BDM/media, publié le 27-février-2020.
                                                                                                                                                               
[4] Fabrice Flipo, « Fake news : la démocratie en danger »,
Libération, publié le 23-janvier-2019[en ligne] Disponible sur : https://www.liberation.fr/debats/2019/01/23/fake-news-la-democratie-en-danger_1704846

[5] Pierre Guesde, « Internet, entre rapidité et deanger »
Maze, publié le 11-mai-2013 en ligne disponible sur :
https://maze.fr/2013/05/internet-entre-rapidite-et-danger/

[6] Adrien Guille, « Diffusion de l’information dans les médias sociaux : modélisation et analyse »
HAL, publié en 2014 disponible sur :
https://tel.archives-ouvertes.fr/tel-01100255/document

[7] 20 Minutes (site web) : Coronavirus : Fin de la course aux likes et entraide, comment le confinement a-t-il affecté nos liens sur les réseaux sociaux ? paru le 27 Mars 2020.

[8] Le Point.fr : Covid-19 : l’infodémie, cette pandémie d’infox qui menace les populations Paru le Vendredi 20 Mars 2020 Par Alice Desclaux. )**
