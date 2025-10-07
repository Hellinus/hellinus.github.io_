---
title: "#043 An Architectural Approach to Level Design - Chapter 4 - Basic Gamespaces"
date: 2024-12-04 00:00:00 +0800
categories: [Game Design, Notes]
tags: [Game Level]
---

> still constructing
{: .prompt-warning }

> Architecture is the thoughtful making of space. —LOUIS KAHN

1. will look at some **simple spatial principles from architectural design.**
2. will explore **historic gamespaces** such as the maze and labyrinth, learning how these ancient space types influence modern game structures.
3. will explore **other popular spatial types** found in modern games and discover how they are used to enforce different gameplay mechanics.
4. will consider **player point of view** and discover what advantages and disadvantages are found in first, third, and other camera views.

## ARCHITECTURAL SPATIAL ARRANGEMENTS
Games and architecture **differ** in the fact that real-world architecture must conform to real-world rules.

With these differences in mind, spatial designers for games can take advantage of architectural lessons **within the freedom** of game design environments.

### Figure-Ground
*Figure–ground* is derived from artistic notions of the *positive and negative space* of a composition, where positive space describes the area inhabited by the subject of a piece and negative space describes space outside of or in-between subjects.

Figure–ground theory in architecture comes from the arrangement of positive space figures, often pochéd building masses, within a negative space ground.

> According to architectural designer Matthew Frederick, spaces formed by arranged figures become positive space in their own right, since they now have a form just as the figures do.
>
> From an urban design standpoint, these framed spaces are often squares, courtyards, parks, nodes, and other meeting areas where people can “dwell,” while remaining negative spaces are for people to move through.

When utilizing figure–ground, both **figural elements and spaces can be implied**, either by:
1. demarcating a space with structural elements;
2. creating negative spaces that resemble the form of nearby figures.

Gamespaces are often based on mechanics of movement through **negative space**, using **positive elements** such as ledges or supports for a player’s journey.

Designers can **communicate** with players via **implied boundaries** or **highlighted spaces** that use figure–ground articulations.

### Form-Void
*Form–void* (also called *solid–void*) is in many ways a **three-dimensional** evolution of figure–ground.

Just as figure–ground is spatial arrangement by marking off spaces with massive elements, form–void is spatial arrangement by adding masses or subtracting spaces from them.

### Arrivals
Based on what we have seen in figure–ground and form–void, level design is an art of contrasts. It is also an art of **sight lines, pathways, dramatic lead-ups, and ambiguity about the nature of where you are going.** All of these elements contribute to the experience of an *arrival*, the way in which you come into a space for the first time.

Much of how we will **communicate** with the player is through arrivals in space. It is also through arrivals that a space **ushers players toward their next destination** or **allows them to choose their own path.**

Much of how you **experience** a space when you arrive in it comes from **the spatial conditions of the spaces that preceded it**: if you are arriving in a big space, the spaces leading up to it should be enclosed so the new space seems even bigger.

Another important element of how players arrive at spaces is **their point of view from the arrival point**.

When a player looks through a doorway their ability to plan their next steps has a lot to do with **how well they can “read” the space** they’ve just arrived in.

**Controlling the information** shown in a view is very important and if done well, can make a more satisfying experience.

### Genius Loci
*Genius loci*, also known as *spirit of place*.

> Roman believed that spirits would protect towns or other populated areas, acting as the town’s genius.

Latetwentieth-century architects adopted the phrase to describe the **identifying qualities or emotional experience** of a place. Some call designing to the concept of genius loci *placemaking*, that is, **creating memorable or unique experiences** in a designed space.

Beyond individual gameplay encounters, level designers can implant genius loci within the entirety of their gamespaces and use it as a tool for **moving players from one point to another.**

Genius loci can be built through manipulations in lighting, shadows, spatial organization, and the size of spaces...

> Cyan Han: elements should follow and contribute to the level's experience.

Spaces in a game with little or no genius loci can be *circulation* spaces, that is, spaces for the player to **move through to get to the next destination.**

> Depending on the gameplay you are creating, circulation spaces may be a chance to rest between intensive encounters or tools for building suspense before a player gets to the next memorable gameplay moment.

## HISTORIC GAMESPACE STRUCTURES
Beyond defining a specific spatial condition of a game environment, these classic spaces serve as important models for how game worlds can be structured: in linear, branching, or interconnected ways.

### Labyrinth
Classic labyrinths are unicursal—consisting of a single winding path.

Labyrinths also demonstrate that even in linear gamespaces, both literal and gameplay twists, turns, and challenges can add interest to an otherwise straightforward pathway.

> As Salen and Zimmerman point out, games are often the least productive way to accomplish a task.

Such a structure is useful for games where an embedded narrative, theme, or argument is being communicated to the player.

### Maze
Mazes are said to be multicursal, having more than one defined path, unlike unicursal labyrinths.

From the Renaissance through the nineteenth century, architects also developed hedge mazes, multicursal pathways through tall bushes in the gardens of large estates. Originally unicursal labyrinths, these structures evolved into branching paths that often contained several points of interest

The branching nature with potential dead ends implies a rich risk–reward structure, where the game asks you to weigh different uncertain options with the hope of choosing an advantageous answer.

The dead ends in mazes do not always have to be negative. Games with even simpler worlds can also utilize small branching paths.

### Rhizome
> A term from botany, rhizomes are networks of roots formed by underground stems of plants.

As a philosophical concept, rhizomes describe a lateral representative structure of information and data without distinctive entry and exit points.

The most important of the guidelines of a rhizome is that every point in them is connected to every other point at the same time.

Spatially, the term rhizome can apply to any place that can be instantly traveled to from any other place.

Instant transportation.

## SPATIAL SIZE TYPES
Size distinctions for gamespaces create some very interesting emotional scenes in game levels.

### Narrow Space
Narrow gamespace is that which is not much larger than a player character’s own size metrics—often with space for only two of such a character to stand in a passageway.

Narrow spaces create tension by giving space scarcity, limited amounts such that space itself becomes a valuable resource.

Evoking vulnerability by limiting player movement options in horror games.

Narrow spaces in stealth games offer concealment from enemies, but at the cost of both mobility and visibility.

### Intimate Space
Intimate spaces are neither confining nor overly large and are, in fact, what one might call metric appropriate, at a size that comfortably supports the size and movement metrics of player characters.

> In some games, the amount of space described in this way may change if the abilities of player characters can expand through additions such as high-jump capabilities or others.

Multiplayer:
- Create a spatially even playing field.
- Contrasting narrow and intimate spaces creates interesting gameplay situations and allows players to build strategies of how to proceed.

Single-player:
- friendly space
- give players an advantage over foes
> Batman: Arkham: player is stronger than foes.

### Prospect Space
Wandering through a large open space and open to attack.

Multiplayer: a spatial advantage over another / vulnerability (deathmatch map)
Single-player: boss rooms /  makes the player’s own movement metrics seem agonizingly slow. (the contrast in movement metrics)

Prospect spaces are similar to narrow spaces in their potential for creating fear in the player.
- Narrow space: claustrophobia
- Prospect space: agoraphobia

## MOLECULE LEVEL SPACES
How to link these spaces together in interesting and meaningful ways
Based on interpretations of mathematical graphing theory - **molecule design**

This chapter discusses the basics of molecule design and enhance it by combining its functionality with proximity diagrams.

### The Basics of Molecule Design
Molecule design is primarily focused on the relationship between play spaces, treated in the graphs as nodes and edges.

Nodes are the play spaces themselves—areas with significant enemy encounters, item pickups, spawn points, or opportunities for action.

Edges describe the relationship between these spaces, visual or spatial (as
in you can travel from one to another).

> In proximity diagrams, the size and importance of spaces are described by the size of bubbles used to represent those spaces. The bubbles are connected with lines of varying thickness to show how important it is for spaces to be connected.

Dotted lines show that spaces are viewable from one another, and solid lines show
that you can move from one to another. Arrows on the solid lines show if
spaces are one way, and thick lines show that spaces between the nodes are
direct paths.

**A description of how spaces interact with one another.**

***Steiner points***

![Steiner Point](/assets/img/Notes/LevelDesign/steiner_point.png)
*This diagram shows the Steiner tree puzzle and the answer utilizing a Steiner point.*

Steiner points are essentially shortcuts in level paths. 
- jumping from high ledges onto lower ones to save time
- incentivized with power-ups or other rare items

### Spatial Types as Molecule Nodes and Edges
Nodes are opportunities to emphasize the gameplay mechanics and genius loci of your level.

Nodes can contain their own smaller maze spaces.

The circulation spaces that bring players from one node to another may be very linear, as may the nodes themselves.

Molecule diagrams may also describe spaces where spatial size changes significantly.
- Multiplayer: spawn area - intimate space, battle area - prospect space
- Single-player: transation from intimate / narrow space to prospect space create **"Jesus Christ spot"**.

Steiner point can be used as an obstacle:
- Player has to jump through top of the pillars, closer way (steiner point) may cause falling to startpoint.
- if returning, steiner point becomes a shortcut again.

> wtf are you writing about

## HUB SPACES
hub-and-spoke spaces

Hubs are a type of intimate space that behaves like a lobby where the player may access a game’s different levels (the spokes). Usually non-threatening and offer players the ability to explore within the metrics of their character’s abilities.

Performance standpoint: for loading levels in an efficient way.
Gameplay standpoint: structured around collecting resources; offer freedom for players to choose what missions to take.

In many ways, hubs offer the best of both linear and open styles of gameplay.

## SANDBOX GAMESPACES

### Pathfinding with Architectural Weenies

### Organizing the Sandbox: Kevin Lynch's Image of the City

#### Landmarks

#### Paths

#### Nodes

#### Edges

#### Districts

## WORKING WITH CAMERA VIEWS

### 3D Views

#### First Person

#### Third Person

### 2D Views

#### Side-Scrolling Space

#### Top-Down Space

### Axonometric / Isometric Views

## ENEMIES AS ALTERNATIVE ARCHITECTURE

## SUMMARY
