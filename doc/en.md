---
title: Documentation
author: Guillaume Brioudes
lang: en
date: 2020-02-24
keywords:
  - visualisation
---

The Otletosphere is a tool for visualising relationships between people and institutions around the protagonist Paul Otlet. It was designed and developed by the (ANR research project [ANR-17-CE38-0011]) [https://hyperotlet.hypotheses.org/]. It is available in French and English. Two buttons at the top right of the header allow you to change language.

# Interface elements

It has two views from the same database:

- The *Network*, which occupies a central place on the site;
- The *Fiches*, arranged in alphabetical order.

These two sections can be reached from the navigation at the top of the page. The *About* panel is added, a place for designers to express themselves freely.

## Network

This is the main view where all relationships between entities are represented in the graph, respectively as links and nodes. Find out in the [navigation section](#navigate-in-the-network) how to use it efficiently.

Groups of nodes and links are displayed in different colours. They correspond to the different types of relationships that entities have with Paul Otlet. It is possible to [sort entities](#filter-the-display) according to their relationship with Paul Otlet.

Hovering over a node highlights it and its relationships. You can also read its title in the box that appears.
Hovering over a link highlights it and reads the description of the relationship in the box that appears.

Translated with www.DeepL.com/Translator (free version)

### Focus

Selecting a node allows you to [display its description](#description-panel) and keep a *focus* on it: you will zoom in on the entity and, as long as it is selected, its opacity will never drop to highlight another one. You can thus combine highlighting the selected entity with close nodes to compare their relationships.

To deselect a node, you must click on an empty area of the *Network*.

## Records

This is the sub-view, focused on description rather than relationships. It shows all the entities arranged alphabetically in the form of maps, with their titles. Vertical navigation on the left allows you to move from one letter to another.

Clicking on one of the maps will allow you to select the entity and display its description. The [description panel](#description-panel) is always displayed and cannot be closed. This will have the parallel effect of making a [*focus*](#focus) on the entity in the graph.

## Description panel

It appears on the right side of the screen. It can be opened (and closed) by clicking on the arrow button or by [selecting an entity](#found-an-entity).

It contains an illustration for each entity, as well as a description. These are key-value pairs (e.g. Country → Belgium), an introductory paragraph and the link to the adjoining Wikipedia page. It also contains a list of links to the relationships of the described entity. When hovering over these links a description of the relationship will be displayed. The coloured dots correspond to entity groups (relationship with Paul Otlet).

Clicking on the header of the description pane (illustration, name...) allows to make a [*focus*](#focus) on the node within the *Network*.

::: astuce
You can **share the description pane of an entity** by using the *Permalink* button at the top of the description pane. It will save an address to share in your clipboard. Any Internet user accessing it will immediately be able to find the entity's description pane. They can also click on their header to find the entity in the graph with a [focus](#focus).
:::

# Found an entity

You can find an entity :

- In the graph, [by moving around](#navigate-in-the-network) ;
- Via the search engine, by entering all or part of its name;
- Via the [description pane](#description-panel) in which the entities related to the last selected one are listed.

# Navigate in the network

## Filter the display

The sorting of the entities acts in both the *Network* and *Records* sections. The alphabetical navigation of the *Maps* is updated according to the remaining maps, as well as the zoom scale of the *Network*.

Sorting commands are cumulative.

The location of the sort commands depends on the size of your screen.

- In the header, if your screen is large enough ;
- Otherwise in a pane that can be opened by clicking on the *funnel* button at the top left of the *Network*.

Each sort command bears the name and colour of the entity group (relation to Paul Otlet) on which it acts. Clicking on the command will have the binary effect of checking or unchecking the box it integrates.

- Checked box: the group is visible
- Unchecked box: the group is invisible.

::: astuce
You can **improve the readability of the graph** by unchecking the "Otelt" filter. A large number of links will then disappear, leaving only the relationships between entities. You can always refer to the colours to see how they relate to the protagonist.
:::

## Navigation axes

Navigation is based on three axes:

1. up `<=>` down, **vertical**
2. left `<=>` right, **horizontal**
3. far `<=>` near

For the first two axes, simply hold the left mouse click on the empty space in the *Network* while moving it. By dragging the mouse to the left you will discover the area on the right. The same applies to the vertical axis.

The third axis can be activated with the mouse wheel and the zoom `(+)` and dezoom `(-)` buttons at the bottom left of the *Network*. You are limited to a maximum and minimum height.

## Moving the nodes

You can move a node by holding the left mouse click on it while moving it. The node will follow the mouse pointer, dragging with it its attached links and the nodes at their ends. This way you can interact with the *Network* to improve your reading experience.