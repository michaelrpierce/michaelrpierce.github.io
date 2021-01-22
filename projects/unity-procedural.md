---
layout: project
type: project
image: https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fjacobktaylor.files.wordpress.com%2F2014%2F08%2Funity-logo.png&f=1&nofb=1
title: Procedural Dungeon Generation In Unity
permalink: projects/unity-procedural
date: 2021-21-01
labels:
  - Unity
  - Procedural Generation
summary: I created a custom map generator for my rogue-like game.
---

<img class="ui medium right floated rounded image" src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fjacobktaylor.files.wordpress.com%2F2014%2F08%2Funity-logo.png&f=1&nofb=1">

## Wanting to Make a Rogue-like

Prior to the loss of my harddrive as mentioned in my [learning and using blender project](https://michaelrpierce.github.io/projects/learning-and-using-blender),
I wanted to create a playable game using the Unity Engine. Unfortunately the Unity file itself is lost, but a
segment of the map generation code was saved on a separate laptop, so I am able to share that here.

At the time of creating the Unity project I was into a rogue-like videogame known as Binding of Isaac. I liked how 
the randomness of the floors as well as the items provided a different playing experience during each run, and I
wanted to create something similar while practicing design concepts. The game was going to have a similar top-down
playing style as is traditional in rogue-likes, so the map was to be generated accordingly. 

## Generating the Map

I decided to challenge myself to see if I could create a simple map generating algorithm using what I already knew,
and eventually produced a result. First the algorithm would create an empty 2D array to represent a tileset for the
map, and proceed to draw a line between two randomly selected points on the map (First traveling along the X axis,
and then along the Y axis). This was repeated until a predetermined percentage of the map was marked as filled. Any
tile that was not visited would become an out of bounds area. The map was then passed to another algorithm that
created and divided the maps into rooms. Each tile on the passed in 2D array would equated to a 32x32 set of tiles 
known as a roomTile.These rooms were as small as 1x1 room tiles and as large as 3x3. Rooms were separated and stored
in a map class, and were given a border wall on their exterior tiles and a door if the next room was not an out of
bounds region of the map.

This was as far as I had gotten with the map generation in the game as I shifted my focus towards the doors and walls
and floors within unity so that the character could travel throughout the map. I know I would design the map
generation algorithm differently using what I know now, as the algorithm could become very inefficient if drawing
lines over previously visited tiles. In the future I hope to learn more about random map generation and other 
techniques learned in videogame design.



"(Source Code Coming Soon)"
