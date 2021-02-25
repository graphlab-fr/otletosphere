---
title: Documentation
author: Guillaume Brioudes
lang: fr
date: 2020-02-24
keywords:
  - visualisation
---

L’Otletosphère est un outil de visualisation de relations entre des personnes et institutions autour du protagoniste Paul Otlet. Elle a été conçue et renseignée par l’équipe du [projet de recherche ANR [ANR-17-CE38-0011]](https://hyperotlet.hypotheses.org/). Elle est disponible en français et en anglais. Deux boutons en haut à droite de l’entête permettent de changer de langue.

# Élements de l’interface

Elle dispose deux vues à partir de la même base de données :

- Le *Réseau*, qui occupe une place centrale sur le site ;
- Les *Fiches*, ordonnées par ordre alphabétique.

Ces deux sections sont joignables depuis la navigation en haut de page. On y ajoute le panneau *À propos*, une place d’expression libre pour les concepteurs.

## Réseau

Il s’agit de la vue principale où toutes les relations entre les entités sont représentées au sein du graphe, respectivement sous forme de liens et nœuds. Découvrez dans la [section navigation](#naviguer-dans-le-réseau) comment l’utiliser efficacement.

Des groupes de nœuds et liens sont affichés dans différentes couleurs. Ils correspondent aux différents types de relations qu’ont les entités avec Paul Otlet. Il est possible de [trier les entités](#filtrer-laffichage) selon leur relation avec Paul Otlet.

Survoler un nœud permet de le mettre en évidence, ainsi que ses relations. On peut également lire son titre dans l’encadré qui apparaît.
Survoler un lien permet de le mettre en évidence et de lire la description de la relation dans l’encadré qui apparaît.

### Focus

Sélectionner un nœud permet d’[afficher sa description](#volet-de-description) et de conserver un *focus* sur lui : vous allez zoomer sur l’entité et, tant qu’elle est sélectionné, son opacité ne baissera jamais pour mettre en avant une autre. On peut ainsi combiner la mise en évidence de l’entité sélectionnée avec des nœuds proches pour comparer leurs relations.

Pour désélectionner un nœud, il vous faut cliquer sur une zone vide du *Réseau*.

## Fiches

C’est la vue secondaire, centrée sur la description plutôt que les relations. On y retrouve toutes les entités ordonnées alphabétiquement sous forme de cartes, avec leur titre. Une navigation verticale à gauche permet de passer d’une lettre à l’autre.

Cliquer sur l’une des cartes va vous permettre de sélectionner l’entité, d’afficher sa description. Le [volet de description](#volet-de-description) est toujours affiché et ne peut être fermé. Cela aura pour effet parallèle de faire un [*focus*](#focus) sur l’entité, dans le graphe.

## Volet de description

Il apparait sur le côté droit de l’écran. Il peut être ouvert (et fermé) en cliquant sur le bouton fléché ou bien en [sélectionnant une entité](#trouver-une-entité).

Il contient une illustration pour chaque entité, ainsi qu’une description. Ce sont des couples clé-valeur (ex : Pays → Belgique), un paragraphe d’introduction et le lien vers la page Wikipédia attenante. Il contient également une liste de liens vers les relations de l’entité décrite. Au survol sur ces liens s’affichera une description de la relation. Les pastilles de couleurs correspondent groupes d’entité (relation avec Paul Otlet).

Cliquer sur l’entête du volet de description (illustration, nom…) permet de faire un [*focus*](#focus) sur le nœud au sein du *Réseau*.

::: astuce
Vous pouvez **partager le volet de description d’une entité** en utilisant le bouton *Permalien* en haut du volet de description. Il va enregistrer dans votre presse papier une adresse à partager. Tout internaute y accédant pourra immédiatement retrouver le volet de description de l’entité. Il pourra aussi cliquer sur son entête pour retrouver l’entité dans le graphe par un [focus](#focus).
:::

# Trouver une entité

Vous pouvez trouver une entité :

- Dans le graphe, [en vous y déplaçant](#naviguer-dans-le-réseau) ;
- Via le moteur de recherche, en y inscrivant tout ou partie de son nom ;
- Via le [volet de description](#volet-de-description) dans lequel sont listées les entités reliée à la dernière sélectionnée.

# Naviguer dans le réseau

## Filtrer l’affichage

Le tri des entités agit tant dans la section *Réseau* que dans la section *Fiches*. La navigation alphabétique des *Fiches* est actualisée en fonction des cartes restantes, ainsi que l’échelle de zoom du *Réseau*.

Les commandes de tri se cumulent.

L’emplacement des commandes de tri dépend de la taille de votre écran.

- Dans l’entête, si votre écran est suffisamment large ;
- Sinon dans un volet pouvant être déployé au clic sur le bouton *entonnoir* en haut à gauche du *Réseau*.

Chaque commande de tri porte le nom et la couleur du groupe d’entité (relation à Paul Otlet) sur lequel elle agit. Cliquer sur la commande aura pour effet binaire de cocher ou décocher la case qu’elle intègre.

- Case coché : le groupe est visible
- Case décoché : le groupe est invisible.

::: astuce
Vous pouvez **améliorer la lisibilité du graphe** en décochant le filtre « Otelt ». Un grand nombre de liens vont alors disparaître pour ne laisser que les relations des entités entre elles. Vous pouvez toujours vous référer aux couleurs pour connaître leur rapport avec le protagoniste.
:::

## Axes de navigation

La navigation s’opère sur trois axes :

1. haut `<=>` bas, **vertical**
2. gauche `<=>` droite, **horizontal**
3. loin `<=>` proche

Pour les deux premiers axes, il vous suffit de maintenir le clic gauche de la souris sur l’espace vide du *Réseau* tout en la déplaçant. En glissant ainsi la souris vers la gauche vous découvrez la zone sur la droite. Il en va de même pour l’axe vertical.

Le troisième axe peut être sollicité avec la molette de votre souris ainsi qu’avec les boutons de zoom `(+)` et dezoom `(-)` affichés en bas à gauche du *Réseau*. Vous êtes limités à une hauteur maximum et minimum.

## Déplacer les nœuds

Vous pouvez déplacer un nœud en maintenant le clic gauche de la souris sur lui tout en la déplaçant. Le nœud va suivre le pointeur de la souris en entraînant avec lui ses liens attachés et les nœuds à leur extrémité. Ainsi vous pouvez interagir avec le *Réseau* pour améliorer votre expérience de lecture.