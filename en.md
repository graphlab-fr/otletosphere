---
title: Otletosphere User Manual
author: Guillaume Brioudes
lang: en
date: 2020-02-24
keywords:
  - visualisation
toc-title: Contents
---

Welcome to the user manual of the [Otletosphere](http://hyperotlet.huma-num.fr/otletosphere/), a relational map of personalities and institutions linked to Paul Otlet, designed by ANR research programme [HyperOtlet](https://hyperotlet.hypotheses.org/).

# About the data

The Otletosphere is built on a dataset of entities and relationships. The entities are classified in two ways:

- by type of entity: persons, works, events, institutions;
- by type of relationship with Paul Otlet: family, colleagues, collaborators, opponents, unclassified.

Each entity is described using metadata (which depend on its type), a photograph or an icon, and a link to the corresponding Wikipedia page. Each relationship is described on the basis of documentary evidence.

# Interface

The Otletosphere is a bilingual website organized in sections.

## Languages

The website is fully available in French and English. Click on the corresponding buttons at the top right of the page to switch between languages.

## Sections

The website is organized in sections:

- “Network” presents the data as an interactive network;
- “Records” presents the same data but in the shape of cards, sorted in alphabetical order;
- “About” presents some information on the project and a few useful links.

Click on the corresponding buttons at the top of the page to navigate between these sections.

## Side panel

Select an entity in the “Network” section or in the “Records” section to display the information about it in the right-side panel.

Click on the button on the left edge of the side panel to open and close it.

Click on the illustration (photograph or icon) displayed at the top of the side panel to refocus the network display on the corresponding entity.

Click on the “Permalink” button to copy the URL of the displayed entity to your clipboard. Visiting this URL will load the Otletosphere with the entity in question already in focus. You can use this feature to bookmark a record or share it.

The side panel has a “Connections” section which lists the entity's relationships as links. Each link is preceded by a coloured dot representing the type of relationship with Paul Otlet for the corresponding linked entity. Hover over the link to see a description of the relationship. Click the link to display the related entity.

::: tip
Use these links to quickly navigate from entity to entity, whether you are in the “Network” or “Cards” section.
:::

## Search

Enter text in the “Search...” field to get suggestions of entities whose name matches your entry. Click on a suggestion to select the corresponding entity.

## Filters

Click on the coloured buttons at the top of the page to filter the display of entities according to their type or their relationship to Paul Otlet. A checked button means that the corresponding entities are displayed; an unchecked button means that they are hidden. This affects the “Network” section, the “Cards” section and the search engine suggestions.

The location of these buttons depends on the size of the window or screen on which the site is displayed. When this size is reduced, click on the funnel-shaped button at the top left of the interactive network to find them again.

::: tip
As the mapping is organised around Paul Otlet, the corresponding node in the network is linked to a very large number of other nodes. You can improve the readability of the network by unchecking the “Otlet” button, which hides only the node corresponding to Paul Otlet.
:::

# “Network” section

In this section, the data is represented as an interactive network. This is the main section of the website. Each node represents an entity. The relationships between these entities are represented by the links between the nodes. The types of entities and relationships with Paul Otlet are signified with colours. The network is displayed on a dark background colour which delimits the interactive area.

## Display

The network is drawn according to an algorithm which simulates physical forces. As a result, the entities have no predefined coordinates, the orientation of the network is random and the drawing changes each time the page is loaded.

::: tip
This is not a static representation: you can drag nodes around to dynamically change the appearance of the network.
:::

## Navigation

Navigation is based on three axes: horizontal (up-down), vertical (left-right) and depth (front-back). Use drag and drop motions for the first two axes. Scroll or use the +/- buttons displayed at the bottom left of the network to move back and forth.

## Focus

Hover over nodes and links to highlight them slightly (temporary focus) and display a tooltip with a short description of the corresponding entity or relationship.

Click a node to highlight it strongly (persistent focus) and display the corresponding information in the side panel. Click an empty area in the interactive network to deselect the node.

::: tip
Combine persistent (click) and temporary (hover) focus to explore different groups of entities simultaneously.
:::

# “Records” section

This section represents the data as cards, sorted in alphabetical order. This is a more secondary section of the website and can be used as an index.

Click on a letter at the left edge of the page to jump directly to the entities whose name begins with that letter.

Click on a card to display the information for the corresponding entity in the right-side panel. The panel cannot be closed when you are in the “Records” section.

::: tip
When you return to the “Network” section, the display will be focused on the last entity you visited in the “Cards” section.
:::
