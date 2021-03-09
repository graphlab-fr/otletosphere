---
title: Manuel d'utilisation de l'Otletosphère
author: Guillaume Brioudes
lang: fr
date: 2020-02-24
keywords:
  - visualisation
---

Bienvenue sur le manuel d'utilisation de l’[Otletosphère](http://hyperotlet.huma-num.fr/otletosphere/), une cartographie relationnelle des personnalités et institutions liées à Paul Otlet conçue par l’équipe du programme de recherche ANR [HyperOtlet](https://hyperotlet.hypotheses.org/).

# Les données

L'Otletosphère est bâtie sur un jeu de données constitué d'entités et de relations. Les entités sont classées de deux manières :

- par type d'entité : personnes, œuvres, évènements, institutions ;
- par type de relation avec Paul Otlet : famille, collègues, collaborateurs, opposants, non-classés.

Chaque entité est décrite en fonction de son type par une série de métadonnées, auxquelles s'ajoutent une photographie et un lien vers la page Wikipédia correspondante. Chaque relation est décrite sur la base d'une preuve documentaire.

# L'interface

L'Otletosphère se présente sous la forme d'un site web bilingue comprenant plusieurs sections.

## Changer de langue

Le site est disponible intégralement en français et en anglais. Cliquez sur les boutons correspondants en haut à droite de la page pour changer de langue.

## Naviguer entre les sections

Le site comporte plusieurs sections :

- « Réseau » correspond à la représentation des données sous forme de réseau interactif ;
- « Fiches » permet d'accéder aux mêmes données mais sous forme de cartes ordonnées par ordre alphabétique ;
- « À propos » présente des informations sur le projet et des liens utiles.

Cliquez sur les boutons correspondants en haut de la page pour naviguer entre ces sections.

## Afficher les informations sur une entité

Sélectionnez une entité dans la section « Réseau » ou dans la section « Fiches » pour afficher les informations lui correspondant dans le panneau latéral situé sur la partie droite de la page.

Cliquez sur le bouton situé sur le bord gauche du panneau latéral pour ouvrir et fermer ce dernier.

Cliquez sur l'illustration (photographie ou icône) affichée au sommet du panneau latéral pour recentrer l'affichage du réseau sur l'entité correspondante.

Cliquez sur le bouton « Permalien » pour copier dans votre presse-papier l'URL de l'entité affichée. Visiter cette URL permet d'afficher directement l'entité en question. Vous pouvez utiliser cette fonctionnalité pour créer un signet vers une fiche ou bien la partager.

Le panneau latéral comporte une section « Connexions » dans laquelle se trouve une liste de liens correspondant aux relations impliquant l'entité affichée. Chaque lien est précédé d'une pastille colorée qui représente le type de relation avec Paul Otlet pour l'entité liée correspondante. Survolez le lien pour afficher une description de la relation. Cliquez sur le lien pour afficher l'entité liée.

::: astuce
Utilisez ces liens pour naviguer rapidement d'entité en entité, que vous soyiez dans la section « Réseau » ou « Fiches ».
:::

## Rechercher une entité

Saisissez du texte dans le champ « Rechercher… » pour obtenir des suggestions d'entités dont le nom correspond à votre saisie. Cliquez sur une suggestion pour sélectionner l'entité correspondante.

## Filtrer l'affichage

Cliquez sur les boutons colorés situés en haut de la page pour filtrer l'affichage des entités en fonction de leur type ou de leur relation avec Paul Otlet. Un bouton coché signifie que les entités correspondantes sont affichées ; un bouton décoché signifie qu'elles sont masquées. Ceci affecte la section « Réseau », la section « Fiches » et les suggestions du moteur de recherche.

L’emplacement de ces boutons dépend de la taille de la fenêtre ou de l'écran sur lequel le site est affiché. Lorsque cette taille est réduite, cliquez sur le bouton en forme d'entonnoir situé en haut à gauche du réseau interactif pour les retrouver.

::: astuce
La cartographie étant organisée autour de Paul Otlet, le nœud correspondant dans le réseau est relié à un très grand nombre d'autres nœuds. Vous pouvez améliorer la lisibilité du réseau en décochant le bouton « Otlet », qui masque uniquement le nœud correspondant à Paul Otlet.
:::

# Utiliser la section « Réseau »

Cette section représente les données sous la forme d'un réseau interactif. C'est la section principale du site. Chaque nœud correspond à une entité. Les relations entre ces entités sont représentées par les liens entre les nœuds. Les types d'entités et de relations avec Paul Otlet sont représentés par les couleurs. L'ensemble est affiché sur un fond de couleur sombre qui délimite la zone interactive.

## Affichage

Le réseau est dessiné suivant un algorithme qui repose sur la simulation de forces physiques. Par conséquent, les entités n'ont pas de coordonnées prédéfinies, l'orientation du réseau est aléatoire et le dessin change à chaque fois que la page est chargée.

::: astuce
Le réseau n'est pas figé : utilisez un cliqué-glissé pour déplacer un nœud (maintenez le clic gauche enfoncé sur un nœud et déplacez le curseur) et ainsi modifier dynamiquement l'apparence du réseau.
:::

## Déplacement

La navigation s’opère sur trois axes : horizontal (haut-bas), vertical (gauche-droite) et profondeur (avant-arrière). Utilisez un cliqué-glissé pour vous déplacer sur les deux premiers axes (maintenez le clic gauche enfoncé sur une zone vide et déplacez le curseur). Utilisez le défilement ou les boutons +/- affichés en bas à gauche du réseau pour vous déplacer d'avant en arrière.

## Focus

Survolez les nœuds et les liens pour les mettre légèrement en évidence (focus éphémère) et afficher une infobulle contenant une courte description de l'entité ou de la relation correspondante.

Cliquez sur un nœud pour le mettre fortement en évidence (focus persistant) et afficher les informations correspondantes dans le panneau latéral. Cliquez sur une zone vide du réseau interactif pour désélectionner le nœud.

::: astuce
Combinez focus persistant (clic) et éphémère (survol) pour explorer différents groupes d'entités simultanément.
:::

# Utiliser la section « Fiches »

Cette section représente les données sous forme de cartes triées par ordre alphabétique. C'est une section plus secondaire du site, qui fait fonction d'index.

Cliquez sur une lettre au niveau du bord gauche de la page pour sauter directement aux entités dont le nom commence par cette lettre.

Cliquez sur une carte pour pour afficher les informations lui correspondant dans le panneau latéral situé sur la partie droite de la page. Le panneau latéral ne peut pas être fermé dans cette section.

::: astuce
En revenant dans la section « Réseau », vous trouverez l'affichage centré sur la dernière entité affichée depuis la section « Fiches », en mode focus persistant.
:::