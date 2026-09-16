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

### 6. Le Seuil qui réclame
On atteint le portail. Son anneau est vide : **une âme demandée, zéro livrée.**
On ne peut pas partir.

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

### 8. Le rallumage
Retour au Frileux. Le faisceau fonctionne : **on voit le corps se remplir par le
bas**, du contour sombre au vert plein. Il suit.
**Enseigne** : la mécanique centrale du jeu.

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

`chargerZone(1)` lit cette carte au lieu d'appeler le générateur ; tout le reste
du jeu — lumière, portes, détection, convoi — fonctionne sans modification,
puisqu'il ne lit qu'une grille de murs et une liste de personnages.

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
