# Étage 1 — « Le bas du puits »

Conception du premier niveau, à la main, non procédural.
Annexe à `docs/lux-falot.md`.

---

## La thèse : ce n'est pas un tutoriel, c'est l'étage 1

La proposition initiale était un **niveau d'introduction optionnel**, avec un
menu demandant si on veut le faire, et des panneaux de texte entre les zones.
La séquence de salles proposée était bonne ; c'est le cadrage qui pose problème.

Depuis une quinzaine d'années le tutoriel séparé a disparu des jeux qui
comptent. Half-Life 2, Portal, la Grande Plaine de *Breath of the Wild*, les
premiers écrans de *Celeste*, *Hollow Knight* : dans tous ces cas **le tutoriel
EST le premier niveau du vrai jeu**, construit pour que sa géographie enseigne.
Personne ne demande au joueur s'il veut apprendre.

Ici la fiction offre la place idéale : les Dessous sont un bâtiment, on en sort
en montant. **L'étage 1 est construit à la main, les étages 2 et au-delà sont
procéduraux.** Rien à cocher, rien à sauter, et la fiction commence à sa place.

### Trois raisons de ne pas poser la question

1. **Le joueur n'a pas de quoi répondre.** On lui demande s'il veut apprendre un
   jeu qu'il n'a pas vu. Celui qui répond « non » et se perd ensuite en voudra au
   jeu, pas à lui-même.
2. **La question avoue la faiblesse.** S'il faut proposer de sauter un passage,
   c'est qu'on le sait ennuyeux. La bonne réponse est de le rendre court et
   jouable, pas facultatif.
3. **Cela coûte le meilleur moment du jeu.** Les trente premières secondes
   doivent être jouées, pas cliquées.

### Ce qu'on fait à la place

Un écran-titre avec **un seul bouton : « Descendre »**.

L'option de saut n'apparaît **qu'une fois l'étage 1 terminé au moins une fois**
(mémorisé dans le navigateur) : un second bouton discret, « Reprendre plus
haut », qui démarre directement à l'étage 2 procédural. C'est exactement le
traitement que les jeux modernes réservent à leur prologue : sautable seulement
par qui l'a déjà vu.

---

## Le récit : où va le texte

La remarque faite plus tôt sur les modales d'évolution — « trop intrusives » —
vaut dix fois plus pour un niveau d'introduction. Un niveau entier ponctué de
panneaux à valider referait la même faute en plus gros.

Trois canaux, par ordre de préférence :

| Canal | Quand | Coût pour le joueur |
|---|---|---|
| Le bandeau passager (existe déjà) | à l'entrée d'une salle, une phrase | aucun, le jeu continue |
| La cage d'escalier (existe déjà) | à la fin de l'étage | un arrêt déjà prévu, autant s'en servir |
| Un écran noir de trois mots | avant la toute première image | le seul arrêt qu'on s'autorise |

Cette dernière exception est standard et vaut la peine : *Inside*, *Limbo*,
*Journey* ouvrent tous sur un écran presque vide. Trois mots, pas de bouton, ça
s'efface tout seul.

### Mais alors, comment raconte-t-on vraiment l'histoire ?

Objection juste : sans un peu de texte, personne ne comprendra les Dessous, les
Éteints ni les Guets. « Pas de panneaux » ne veut pas dire « pas de mots ». Il
faut simplement que les mots ne coûtent jamais un clic.

**Le canal principal : ce que disent les âmes qu'on rallume.**

Quand un Éteint se rallume, il dit **une phrase** au-dessus de sa tête avant de
se mettre à suivre — deux secondes, pas de bouton, pendant qu'on continue à
jouer. C'est le meilleur canal possible pour trois raisons :

- il est **mérité** : on ne l'entend que si on a sauvé quelqu'un, donc il
  récompense le geste central du jeu ;
- il est **diégétique** : ce sont des gens qui parlent, pas un narrateur ;
- il est **inépuisable** : quinze répliques par espèce suffisent à peupler des
  heures, et on découvre le monde par bribes, jamais par exposition.

Exemples de ce que ça donne, sans jamais expliquer la règle :

> — « Je croyais que j'étais éteinte pour de bon. » *(un Frileux)*
> — « Il y en a d'autres. Plus haut. Beaucoup d'autres. » *(un Errant)*
> — « Ne les regarde pas trop longtemps. C'est comme ça qu'on tombe. » *(un
>   Errant — et le joueur comprendra ce que c'est qu'un Guet trois étages plus
>   tard)*

**Le canal de fond : la cage d'escalier.** C'est un arrêt de toute façon ; deux
à quatre phrases y passent sans rien coûter. Sur dix étages, c'est un récit
complet.

**Le canal d'ambiance : les murmures.** Une phrase pâle qui apparaît dans le
décor lui-même quand on passe près de quelque chose — une torche morte, le poste
d'un Guet, une porte. Elle s'efface seule. C'est la méthode de *Dark Souls* et
de *Journey* : de la matière narrative posée exactement là où elle est
pertinente, jamais en travers du chemin.

**Récapitulatif : qui porte quoi.**

| Canal | Ce qu'il raconte | Coût |
|---|---|---|
| Les âmes rallumées | qui sont les Éteints, ce qu'ils ont vécu | aucun |
| La cage d'escalier | où l'on est, ce qu'on a fait, ce qui reste | un arrêt déjà prévu |
| Les murmures | le bâtiment, les Guets, ceux qui sont passés avant | aucun |
| L'écran noir d'ouverture | trois mots | le seul arrêt qu'on s'autorise |

---

## Les salles

Dix intentions, environ six salles, **moins de quatre minutes**. Si ça dépasse,
la salle de la torche est la première à sacrifier.

### 1. Le réveil
Une pièce minuscule, fermée, rien que Falot et son halo.
**Enseigne** : on se déplace, et on ne voit que ce qu'on éclaire.

### 2. Le couloir des lueurs
Trois ou quatre lueurs en enfilade, visibles de loin parce qu'elles brillent.
On les ramasse, le « +4 » monte vers la barre, la barre tressaille.
**Enseigne** : ces petites choses jaunes servent à quelque chose.

> Déplacé plus tôt que dans le croquis d'origine. Il faut savoir ce que sont les
> fragments **avant** que le jeu demande de faire des choix.

### 3. La salle de la torche
Une salle trop grande pour le halo. Une torche au mur ; en passant devant, elle
s'allume et la salle apparaît d'un coup.
**Enseigne** : les torches se rallument, et la lumière révèle le terrain.

### 4. Le premier Guet
Un couloir traversé par un rouge en ronde. Il faut passer.

La première tentative échoue : on est vu, on s'éteint, on se rallume à l'entrée
de la salle — instantanément, sans écran, sans pénalité. **Et c'est à ce
moment-là que le bouton CAILLOU se met à pulser.**

**Enseigne** : le rouge, son cône, le fait que mourir ne coûte presque rien, et
le caillou — dans cet ordre. On ne donne jamais l'outil avant le problème.

Deux solutions valables, et c'est ce qui en fait une bonne salle :
- lancer un caillou pour qu'il aille voir ailleurs ;
- se tenir près de la torche allumée de la salle précédente, car **une torche
  allumée rend invisible** (vérifié dans le code : `abri` coupe la détection).

### 5. Le Frileux qu'on ne peut pas encore aider
Un bleu dans un renfoncement. On approche, il fuit. On l'éclaire, rien ne se
passe — **et c'est exact** : sans faisceau, `propager` sort avant d'éclairer
qui que ce soit, donc personne n'est calmable à la forme Peureux.

Une phrase passagère, pour que l'échec informe au lieu d'inquiéter :
*« Il a trop peur pour te suivre. Tu n'éclaires pas encore assez. »*

**Enseigne** : il existe des gens à sauver, et il te manque quelque chose.

> **Correction apportée au premier jet.** Objection juste : avec un seul
> Frileux, le joueur risque de retenir « on ne peut pas récupérer les gens » et
> de ne jamais découvrir qu'on le peut ; et en inversant l'ordre, il retiendrait
> l'inverse. Il en faut **deux**, et le second après les fragments.

### 6. Le Seuil qui réclame
On atteint le portail. Son anneau est vide : **deux âmes demandées, zéro
livrée.** On ne peut pas partir.

> **C'est ici que je m'écarte le plus du croquis.** L'idée d'une « porte bloquée
> jusqu'à ce qu'on aille chercher le PNJ » introduit une serrure que le reste du
> jeu n'utilise jamais — alors que la règle établie est qu'une porte s'ouvre pour
> quiconque n'est pas un Guet. Un niveau d'introduction doit enseigner les vraies
> règles, pas des exceptions.
>
> Le portail qui réclame une âme produit exactement le même détour, avec une
> règle qui servira toute la partie.

### 7. La montée en confiance
Un passage latéral, assez de lueurs pour atteindre Curieux. Le bouton change de
couleur, pulse, gagne son aura.
**Enseigne** : l'éclat ouvre des formes, et les formes ouvrent le caillou.

### 8. Le second Frileux — la révélation
Dans le couloir qui suit la montée, **un deuxième Frileux**, tout de suite
après les fragments. On l'éclaire, et cette fois **le corps se remplit par le
bas**, du contour sombre au vert plein. Il suit.

**Enseigne** : c'était ça, le faisceau. La mécanique centrale du jeu, découverte
par contraste avec l'échec de la salle 5 — quinze secondes plus tôt on ne
pouvait pas, maintenant on peut.

### 8 bis. Retourner chercher le premier
Le Seuil réclame **deux** âmes. On en a une. Le premier Frileux est toujours là,
en arrière — et on sait désormais quoi faire de lui.

**Enseigne** : le Seuil compte, et **on retourne chercher ceux qu'on a laissés
derrière**. C'est le sujet du jeu tout entier, enseigné par la géographie sans
une ligne de texte.

### 9. Le passage à deux
Un couloir, un rouge, et cette fois un suiveur derrière soi. La jauge du rouge
monte **deux fois plus vite** — mesuré, 0,17 par corps exposé et par
demi-seconde.
**Enseigne** : escorter coûte. C'est l'arbitrage de tout le jeu.

> Un seul rouge, pas deux. Un premier examen doit être réussissable du premier
> coup par quelqu'un qui a compris.

### 10. Le Seuil, rempli
On livre. L'anneau se complète, Falot se vide de sa lumière, la cage d'escalier
s'ouvre pour la première fois — avec le premier vrai texte du récit.

---

## Les points de reprise

À la mort, on repart **à l'entrée de la salle en cours**, immédiatement, sans
écran ni chargement. C'est la norme depuis *Super Meat Boy* et *Celeste* : la
mort doit coûter des secondes, pas de la patience.

Le jeu respawne déjà au départ de la zone ; il suffit d'enregistrer, à l'entrée
de chaque salle, un point de reprise qui remplace `zone.depart`.

---

## L'abri se voit enfin

Une torche allumée coupe la détection, mais **rien ne le disait** : on jouait la
peur au ventre sans savoir qu'on ne risquait plus rien. Une sixième humeur est
donc apparue, **APAISÉ** — sourcils hauts et détendus, œil à demi clos, et le
seul sourire du jeu. Elle passe **avant toutes les autres**, y compris la peur :
un rouge peut hurler à deux pas, si l'on est dans la lumière, le visage le dit.
Quelques motes tièdes montent du corps pour appuyer.

Vérifié : rouge en alerte hors abri → « peur » ; le même rouge en alerte, à la
torche → « apaisé ».

### L'abri protège qui s'y tient

L'asymétrie est tranchée : **ce n'est pas un statut, c'est une position.** Le
joueur et chaque suiveur posent la même question depuis l'endroit où ils se
trouvent. Celui qui est dans la lumière est couvert ; celui qui dépasse reste
prenable — et son visage le dit, puisque l'apaisement s'affiche âme par âme.

Cela transforme un abri en **problème de placement** plutôt qu'en interrupteur :
avec quatre suiveurs et une braise, il faut que tout le monde tienne dedans.
C'est exactement l'arbitrage que le jeu cherche partout ailleurs.

Mesuré sur 60 images, une braise couvrant le joueur et une âme sur deux : l'âme
du dedans est comptée à l'abri 60 fois sur 60 et porte le visage apaisé, celle
du dehors 0 fois et porte la peur, et la sentinelle ne voit **qu'un corps sur
les trois présents**.

---

## Se remettre au travail sans retraverser l'étage 1

Un niveau écrit à la main devient vite pénible à retraverser à chaque essai.
Deux paramètres d'URL, déjà en place :

```
?etage=4                  démarre directement à l'étage 4
?graine=LUX-7001          fixe le plan
?etage=4&graine=LUX-7001  les deux
```

Rien d'autre ne lit l'URL ; sans paramètre, le jeu démarre normalement. Vérifié :
`?etage=4&graine=LUX-7001` ouvre bien la zone 4 sur cette graine.

---

## Le plan, tel qu'il est écrit

Ce n'est plus une intention : c'est la carte que `zoneEcrite` lit au démarrage.
Elle vit dans `poc/lux-paranoia.html`, sous `ETAGES_ECRITS`.

```
#########################
##############.........##     1  la salle de la torche
##...#########.........##
##.@.6o.o.o.o.*........##     3  le réveil, le caillou, puis le couloir des lueurs
##...#########.........##
##############.........##
##############..2T.....##
##################*######
##################=######
##################1######
############..r........##    10  la galerie du premier Guet
##################.######
##################=######
##################.######
##############....*....##    14  le Frileux qu'on ne peut pas encore aider
##############.......b.##
##############.........##
######......3|.*.......##    17  le couloir calme, et sa porte
######=##################
##....*.########......###
##......##5T####......###    20  l'alcôve de la torche, sur le trajet de l'escorte
##..S...|o.o.or|*.....###    21  le Seuil, les fragments, le Guet de l'escorte
##....4.####..##....b.###    22  le renfoncement de la première âme
##......####.b##......###    23  la seconde âme, au fond de la dernière salle
#########################
```

`#` mur — `@` départ — `S` Seuil — `o` lueur — `T` torche — `b` Frileux —
`r` Guet — `|` et `=` portes — `*` point de reprise — `1-9` murmure.

**Le parcours.** Réveil, couloir des lueurs, salle de la torche, galerie du
premier Guet, salle d'un Frileux — qu'on ne peut pas encore sauver —, couloir
calme, Seuil qui réclame deux âmes. Puis le couloir des fragments, gardé par le
second Guet. La première âme est dans un renfoncement **sur ce couloir même**,
sous le nez du Guet ; la seconde au fond de la dernière salle. On ramène la
première, **le portail affiche 1/2**, et c'est là seulement qu'on comprend qu'il
se charge. On repart chercher l'autre, et le retour repasse devant le même
Guet.

> **Corrigé deux fois, après essai à la manette.** Les deux âmes étaient
> d'abord aux deux bouts du niveau, pour que le Seuil oblige à revenir chercher
> la première : à la manette ce demi-tour **ne se devine pas**, rien sur le
> chemin ne le demande. Elles ont donc été mises côte à côte dans la dernière
> salle — et là elles étaient trop proches : on les rallumait toutes les deux
> d'un même geste et **on ne voyait jamais le portail se charger**. Elles sont
> maintenant à deux endroits distincts du même secteur : assez écartées pour
> qu'on livre, qu'on lise « 1/2 » et qu'on reparte, assez proches pour que le
> retour ne coûte pas la traversée de l'étage.
>
> Le Frileux de la salle 5 reste ce qu'il est — la démonstration qu'il te
> manque quelque chose — et on n'est jamais obligé d'y retourner.

**L'alcôve** s'est déplacée avec le Guet : elle est maintenant sur le trajet de
l'escorte, et un murmure y dit enfin la règle à voix haute — *« Tant que la
flamme tient, il ne te voit pas. Ni toi, ni ceux qui se serrent contre toi. »*
C'est l'arbitrage du jeu en petit : on ne se met pas à l'abri, on **y met tout
le monde**.

**Les deux Guets sont scellés dans leur quartier** par les portes — 13 cases
pour celui de la galerie, 8 pour celui de l'escorte. Vérifié : ni l'un ni
l'autre n'atteint le Seuil ni le premier Frileux, quoi qu'il arrive.

**Le budget d'éclat est calibré à deux points près** : sept lueurs à 4, soit 28,
pour un seuil de Curieux à 26. La forme s'ouvre donc à la troisième lueur du
passage latéral — exactement là où le niveau en a besoin, et jamais avant.

### Ce qui a été mesuré

| Ce qu'on voulait | Ce qu'on a mesuré |
|---|---|
| Personne n'est récupérable sans faisceau | à la forme Peureux le premier Frileux n'est même pas *éclairé* : `eclaire` reste faux |
| Le faisceau change tout | même position, forme Curieux : calmé et suiveur |
| 28 d'éclat pour un seuil à 26 | 28 exactement, forme 1 atteinte |
| Les Guets restent chez eux | 0 des 2 n'atteint le Seuil ou le premier Frileux, portes fermées |
| Les murmures se déclenchent au passage | 4 sur 4, et 0 avant d'y passer |
| La reprise déplace le départ | mort après un point de reprise → renaissance exactement dessus |
| Le Seuil réclame deux âmes | avec 1 livrée il reste fermé ; avec 2 la vidange part et l'étage 2 se charge |

### Combien de temps ça fait

Un pilote automatique a parcouru l'étage entier, **Guets aveuglés en
permanence** : ce qui reste est la part de trajet, le plancher incompressible du
niveau.

| Moment | Temps |
|---|---|
| Couloir des lueurs | 2,4 s |
| Salle de la torche | 4,7 s |
| Galerie du Guet traversée | 7,7 s |
| Seuil atteint, vide | 17,9 s |
| Fragments ramassés (forme Curieux) | 21,0 s |
| **Première livraison — le portail affiche 1/2** | 28,5 s |
| Seconde livraison, le Seuil s'ouvre, étage 2 chargé | 42,5 s |

**42 secondes de marche pure.** Le reste du temps de jeu, c'est ce qui fait le
jeu — attendre qu'un regard passe, se mettre à l'abri, mourir une fois ou deux.

Une précision honnête : ce pilote ne sait ni lancer un caillou ni se mettre à
l'abri. Guets actifs, il ne franchit pas un couloir gardé — ce qui dit que le
couloir est un vrai obstacle, et rien du temps qu'y mettra quelqu'un qui a
compris. Ce chiffre-là se mesure à la main.

### Ce que le joueur ne comprenait pas

Quatre choses, relevées à la manette. Aucune n'était un bug : toutes étaient
des règles que le jeu appliquait sans jamais les dire.

| Ce qui manquait | Ce qui a été fait |
|---|---|
| À quoi sert le caillou, et qu'on en a un | Un murmure dès la sortie de la première salle (*« la seule chose ici qui ne brille pas »*), un autre juste avant la galerie du Guet (*« lance-le loin de toi : il ira voir là-bas »*), et le bouton qui se met à battre **quand un regard commence à te tenir** — trois fois par partie au plus |
| Qu'on charge le portail avec des âmes | Le compte est écrit **sur le portail** (« ÂMES — 1 / 2 », « ENTRE » quand il cède), une phrase le dit à la première approche, et le murmure du Seuil ne se contente plus de « sortir c'est monter » |
| Qu'on remplit une jauge qui change de forme | La barre passe de 80 à 148 px, gagne un contour, et surtout une légende : **PEUREUX → CURIEUX**. Toute la jauge sursaute au ramassage, pas seulement le trait |
| Que le portail se charge à plusieurs âmes | Les deux âmes sont séparées : on en livre une, on lit « 1/2 », on repart |

### Passer le prologue

Le bouton **« Passer le prologue — reprendre à l'étage 2 »** est visible en
permanence sur l'écran-titre. La règle prévue — ne le débloquer qu'après une
première fin — est la bonne pour un jeu publié, mais elle rend l'étage 1
obligatoire à chaque essai pendant qu'on le construit. Une ligne suffit à la
rétablir le jour venu (`hidden = !prologueFini()`).

Et depuis la console, `__lux.charger(4)` ou `__lux.graine('LUX-7001')` referment
l'écran-titre au passage : sans ça le monde reste gelé derrière lui.

---

## Ce que ça demande côté technique

L'étage 1 étant écrit à la main, il faut un **format de niveau**. Le plus simple
et le plus modifiable est une carte en texte, une ligne par rangée de cases,
avec des lettres pour le mobilier :

```
#########
#....T..#     #  mur          T  torche
#..@....#     @  départ       o  lueur
#...o...#     r  Guet         b  Frileux
#########     S  Seuil
```

`chargerZone` lit cette carte au lieu d'appeler le générateur dès qu'un étage
écrit existe pour ce numéro ; tout le reste du jeu — lumière, portes, détection,
convoi — fonctionne sans modification, puisqu'il ne lit qu'une grille de murs et
une liste de personnages. Une seule chose a dû bouger dans le générateur : la
fabrication d'un personnage, extraite dans `nouveauPerso` pour que les PNJ
écrits à la main soient rigoureusement les mêmes que les autres. L'ordre des
tirages y est préservé au tirage près — le changer aurait regeneré un autre
monde pour chaque graine.

Les rondes des Guets, elles, sont **écrites** et non tirées : un premier étage
doit se relire à l'identique d'une partie sur l'autre, sinon il n'est ni
équilibrable ni débogable.

C'est aussi ce qui rend le niveau amendable sans toucher au code : on déplace
une lettre, on rejoue.

---

## Résumé des désaccords

| Proposition initiale | Contre-proposition | Pourquoi |
|---|---|---|
| Un tutoriel optionnel | L'étage 1 du vrai jeu | Le tutoriel séparé a disparu des jeux modernes ; et la fiction offre déjà la place |
| Un menu « faire le tuto ? » | Un bouton « Descendre » | Le joueur n'a pas de quoi répondre ; la question avoue la faiblesse |
| Saut proposé d'emblée | Saut débloqué après une première fin | Traitement standard d'un prologue |
| Panneaux de texte entre zones | Bandeau passager + cage d'escalier | Même faute que les modales d'évolution, en plus gros |
| Porte bloquée jusqu'au PNJ | Le Seuil réclame une âme | Même détour, mais avec une règle qui sert toute la partie |
| Fragments découverts en 5ᵉ | Fragments en 2ᵉ | Il faut savoir ce qu'ils sont avant qu'on demande d'arbitrer |
| Deux rouges à l'examen | Un seul | Un premier test doit se réussir du premier coup |

Et ce qui est repris tel quel du croquis, parce que c'est juste : la découverte
du halo en premier, la torche, le rouge qui amène le caillou, le PNJ qu'on ne
peut pas encore sauver, la zone d'entraînement, l'examen, le portail en
récompense. La colonne vertébrale est la bonne.
