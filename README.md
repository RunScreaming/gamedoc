*Run Screaming*

Game Design Document

[[TOC]]

## High-Speed-Elevator Pitch

A player is chased through a maze full of thrill & danger. It’s a mess. Chaos everywhere. The location of safety is unclear. Fast running and not getting lost at the same time is impossible. In order to escape, help is needed! Luckily, other players are at hand via radio to guide.

## Executive Summary

The game is supposed to be played by multiple (3+) players.

One player ("**Player 1**") is sitting behind a desktop computer, the others (“**The Other Players**”) should not be able to see onto the screen.

The main goal of the game is to pilot Player 1 through a labyrinth, which is peppered with traps, shortcuts, monsters and some landmarks. The other players have access to maps (either via printouts or by accessing some website (on their phone)) which show some of these monsters/traps/shortcuts/landmarks. But every player owns a different map! First, the players with the maps have to identify the location at which the playing player on the computer has been spawned. Second, they have to navigate the player safely to the goal. To make the game harder, there is a time limit for reaching the goal.

### Diversifier

*" Can I Try?: Any spectator of the game automatically becomes a player as well. “*

## Gameplay

The actual dramaturgy is still open. Therefore the following chapter describes the gameplay in a more generic way.

### The World

The world in its simplest form will we a traditional maze. Grey walls, a grey or wooden floor and a burning sky. Depending on the actual dramaturgy this may change to a more sophisticated setting (city, island, post-apocalyptic countryside, …) or even a more open world (possibly only in version 2.0). The map is created by game designers.

### Player 1

The player on the screen, controlling the actual (only human-controlled) actor in the level. In the same room as *The Other Players*.

### Enemies

Various non-human-controlled moving and stationary actors in *the World*. Creating thrill and endangering the *Player 1*. Design depends on the actual dramaturgy.

### The Other Players

1, 2 or more people sitting in the same room with *Player 1*. They don’t control any actor in the level. In possession of *The Map* they help *Player 1* to navigate through *the World*. To do so, they first have to pin down the *Player 1*’s initial location in *the World* by comparing the surrounding with striking landmarks on *the Map*. After doing so, they have to help *Player 1* to bypass as much *enemies* as possible.

### The Map

The Map (or maps) is a simple 2d blueprint of *The World* printed on paper. The map is created by game-designers at the same time as *The World*. It gives *The Other Players* additional information about *The World* not known to *Player 1* (yet). Mainly an overview of *The World*, the location of *The Safe Exit*, and all instances of *Enemies*. It does not tell *The Other Players* the initial or current location of *Player 1* in *the World*, though. This information is split over multiple versions of *The Map*. Thus, since multiple *other Player*s hold different copies of *The Map*, none of them knows everything. The more *other Player*s join the game, the easier it gets to keep track of the world around *Player 1*.

### The Safe Exit

The primary game objective is to help *Player 1* to reach the safe exit alive/without losing ice cream/without screaming/with clean clothes/ ...

Objects, Actors, Objectives, …

## Look and Feel

The actual dramaturgy is still open. since the detailed look & feel depends on the dramaturgy, this is still TODO.

### Player 1:

Option A (unlikely): Played in Isometric Worlds in third-person perspective.

Option B (likely): Played in an 3d world in first-person perspective.

### Other players:

The other players don’t need a computer. They sit in the same room as player 1, but instead of a computer they are equipped with sheets of paper. On each sheet of paper ...

Setting, Atmosphere, (Story?), World, Landscape, Ground Type, ...

## Platform

According to plan, the game will be developed using Unity 3d. Althought will result in support for various platforms (https://unity3d.com/unity/multiplatform), the development & testing will focus on the desktop operating systems Windows and Linux.

*Alternative Version (probably later milestone): Web*

### Development System

The game will be developed using Unity 3d, probably on Windows, since the Linux version of the development tools is only available as experimental build ([http://blogs.unity3d.com/2015/08/26/unity-comes-to-linux-experimental-build-now-available/](http://blogs.unity3d.com/2015/08/26/unity-comes-to-linux-experimental-build-now-available/)).

The game development process, including design documents, concepts, story, artwork and source code, will be carried out on public platforms, for example GitHub.

## Required Artwork

TODO, depending on the actual setting/story.

Graphics and Audio Assets, Animations, …

See:

* [http://opengameart.org/](http://opengameart.org/)

* [http://www.freesound.org/](http://www.freesound.org/)

## Team

<table>
  <tr>
    <td>Name</td>
    <td>Role</td>
    <td>Notes</td>
  </tr>
  <tr>
    <td>Anja Karl</td>
    <td>Head of Unity</td>
    <td>unity on Windows</td>
  </tr>
  <tr>
    <td>Roland Urbano</td>
    <td>Best Boy</td>
    <td>unity on Windows</td>
  </tr>
  <tr>
    <td>Peter Grassberger</td>
    <td>Senior aMaze Master</td>
    <td>unity on Linux</td>
  </tr>
  <tr>
    <td>Stefan More</td>
    <td>"Researcher", Story</td>
    <td>unity on Linux</td>
  </tr>
  <tr>
    <td>Lukas Neugebauer</td>
    <td>3d art</td>
    <td>Blender Ninja</td>
  </tr>
</table>


## Appendix 1: Story Ideas

<table>
  <tr>
    <td>Codename</td>
    <td>Run-Motivation</td>
    <td>Enemies</td>
  </tr>
  <tr>
    <td>"The obvious one"</td>
    <td>Zombies, Bio-Foo</td>
    <td>Zombies, Traps</td>
  </tr>
  <tr>
    <td>Uni-Life, #1: Party Life</td>
    <td>Warm beer, phone battery, late for Party, ...</td>
    <td>Alcohol, loud music, … ?</td>
  </tr>
  <tr>
    <td>Uni-Life, #2: Academia</td>
    <td>Some Deadline (Paper, Project, ..)</td>
    <td>“Distractions”: Friends, Professors, other Deadlines, Parties, Sickness, more exciting lectures, ...</td>
  </tr>
  <tr>
    <td>Moon Base</td>
    <td>Running out of oxygen</td>
    <td>Dying environment, something your base found?</td>
  </tr>
  <tr>
    <td>Underwater Base</td>
    <td>Running out of oxygen</td>
    <td>Dying environment, scary underwater-animals, something your base found</td>
  </tr>
  <tr>
    <td>Underground Research base (see: Half-Life)</td>
    <td>Experiment gone wrong</td>
    <td>Headcraps! Dangerous environment! Mutants! Confused scientists!</td>
  </tr>
  <tr>
    <td>Medieval castle</td>
    <td>Your prince is getting married!</td>
    <td>Crocodiles, Swamp, Drawbridge, ...</td>
  </tr>
  <tr>
    <td>Keep running or everybody explodes</td>
    <td>Run, or everybody explodes!?</td>
    <td></td>
  </tr>
  <tr>
    <td>Open world motor-biking</td>
    <td>Win the race against the clock</td>
    <td>-</td>
  </tr>
  <tr>
    <td>Dream</td>
    <td>Dont wake up</td>
    <td>something to wake you up</td>
  </tr>
  <tr>
    <td>Vulcano (Indiana Jones)</td>
    <td>Lava</td>
    <td>Traps, Arrows, Villains, ..</td>
  </tr>
  <tr>
    <td>Postman</td>
    <td>Deliver all the post</td>
    <td>Other Post-Persons? ...</td>
  </tr>
  <tr>
    <td>Library</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>your favorite PC game</td>
    <td></td>
    <td></td>
  </tr>
</table>


## Appendix 2: Milestones

### Milestone 0: 2015-11-04

First draft of Game Idea.

[https://docs.google.com/document/d/1Av_Bsn_tiRX_xHnQ8h3AeJ_XR4MLINMTdViNGzcQ6KI/pub](https://docs.google.com/document/d/1Av_Bsn_tiRX_xHnQ8h3AeJ_XR4MLINMTdViNGzcQ6KI/pub)

### Milestone 1: 2015-11-27

Game Design preview.

**DOC:** First draft of Game Design Document.

**STORY:** brainstorm ideas

**GAME**: -

**ARTWORKS**: -

### Milestone 2: 2015-12-..

Technological preview.

**DOC**: Small adjustments based on prototype.

**STORY**: narrow down ideas based on prototype.

**GAME**: First prototype of game. First or second iteration.

**ARTWORKS:** First prototype artworks. No sounds.

### Milestone 3: 2016-01-30

Second prototype. Playable preview.

**DOC**: adjustments based on prototype.

**STORY**: ‘Stable’ story.

**GAME**: Later iterations. Internal tests. Maybe, first external tests.

**ARTWORKS**: Asset-list freeze. First sounds.

### Milestone 4: 2016-02-15

Beta release.

**DOC**: ‘freeze’  (but write down notes for later versions)

**STORY**: ‘freeze’ (but write down notes for later versions)

**GAME**: Feature freeze. Extensive external tests.

**ARTWORKS**: Final assets. Sound tuning.

### Milestone 5: 2016-02-27

"Final" release & presentation.

### Milestone n+1 *aka: The Bonus Content*

If there is time, or if there is a version 2.0, some of the following ideas are considered to be implemented. Otherwise those exist to be implemented by those who have time:

* When more players access the game (while it is already running), the game could e.g. generate items which have to be picked up to open the goal. These are only shown on the new maps.

* There could be different modes.

    * e.g. one mode which always takes place in the same HUGE labyrinth. Monsters and Traps, etc. are generated randomly by the computer and at the start of the game, everybody gets a printed empty map, and the camera is zooming out of the labyrinth/moving over it. Now everybody has to note down as fast as possible, where those monsters are located. Nevertheless, there are too many monsters to note everything down by yourself, so you have to work together and split the task.

* There could be special items, which are needed for example to be able to defeat monsters. (E.G. Red sword for defeating zerberus or something like that)

* Some easter eggs hidden in the labyrinth

* Limited view for the computer player (player does not see traps or monsters unless they run into them).

* Possibility to "fight" monsters. Every monster has a special weakness which is only known to the player with the correct map. (Complex weaknesses, like press a - b - jump - c or something like that)

* add other diversifiers, for example via dramaturgy.

* more open level / open world

