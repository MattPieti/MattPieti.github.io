---
layout: post
title: Simulated Maze
description: Built a custom PCB to connect to an Arduino Mega with an ATmega328P microcontroller, then used assembly (AVR) to implement a maze. Designed a flowchart solution and translated it into a 4-state finite state machine with subroutines and indirect addressing. Final code also counted how many "bees" the "bear" encountered in the maze.
skills:
  - Arduino
  - Assembly
  - Indirect Addressing
  - Subroutines
  - Soldering
  - PCBs

main-image: /Maze.PNG
---

---

## "Arduino Proto-Shield" PCB

This custom PCB was built by soldering 30 parts according to instructions from the lab manual. It worked first try without errors despite the manual's warning that it probably wouldn't. Images below are from the manual.

{% include image-gallery.html images="ProtoshieldTop.PNG, ProtoshieldSide.PNG" height="400" %}

---

## Project Summary



### Introduction


This was a lab project done for EE346: Microprocessor Principles and Applications. The project spanned the entire semester. Individual project parts were done as 6 lab assignments with pre-labs.
  
  
The goal of this project was to simulate a bear traversing a 20-by-20 maze with each square in the maze grid represented by an ordered pair in hexadecimal. Some squares contained bees with a number indicating how many were there. All programming was done in AVR Assembly.


{% include image-gallery.html images="MazeFull.PNG" height="400" %}


### Part 1: Individual path and flowchart


Found a "target square" based on my ID. Designed a maze solution where the bear passes through the target square and as close as possible to 15 bees without going over. Represented solution as a flowchart.


### Part 2:


Wrote code to perform some simple calculations and test board functions. This was the first lab completed after circuit assembly.


### Part 3:


Implemented subroutines to determine wall locations in the bear's current room and allow it to turn left, right, or backward.


### Part 4:


Implemented circuit debounce. Implemented a delay subroutine to slow maze traversal for user viewability. Implemented a 2-state finite state machine (FSM) for room type and direction, then added a third state for walking.


### Part 5:


Implemented the maze digitally as a lookup table and modified existing code to incorporate room locations. Added a fourth state to the FSM to allow the bear to walk down a hallway.


### Part 6:


Implemented maze solution from the flowchart in Part 1 with the shortest path as an alternate solution. Implemented bee counter.
