---
layout: post
title: Undergraduate Research - Accelerometers & Activity Recognition
description: Implemented an MMA8452Q three-axis accelerometer on an Arduino UNO to measure user movement, resulting in the development of a prototype activity recognition algorithm. Invited to role due to strong academic performance. Worked collaboratively with a peer and presented results.
skills:
  - Arduino
  - PCB
  - Research
  - Collaboration
  - Communication

main-image: /accel.PNG
---

---

## Summary

After performing well in EE202, a MATLAB course, I was invited by the teacher to join a small group of students researching wearable biomedical technology. We were split into smaller subgroups to study individual components. I was paired with one other student to study accelerometers and their role in activity recognition.



After some research, we assembled and soldered a simple PCB with an accelerometer to connect to an Arduino, creating a system that outputs three dimensions of acceleration data, averages, and standard deviations to a computer. The results formed a prototype activity recognition system.



We regularly presented our findings to the larger group throughout the semester. The research ultimately resulted in the [BioMeSensi](https://dl.acm.org/doi/10.1145/2737095.2742920) device, though the undergraduates' contributions were not significant enough for us to be credited.

{% include image-gallery.html images="accelpcb.JPG" height="400" %}

---

## Project Summary



### Introduction


This was a lab project done for EE346: Microprocessor Principles and Applications. The project spanned the entire semester. Individual project parts were done as 6 lab assignments with pre-labs.
  
  
The goal of this project was to simulate a bear traversing a 20-by-20 maze with each square in the maze grid represented by an ordered pair in hexadecimal. Some squares contained bees with a number indicating how many were there. All programming was done in AVR Assembly


{% include image-gallery.html images="MazeFull.PNG" height="400" %}


### Part 1: Individual path and flowchart


Found a "target square" based on my ID. Designed a maze solution where the bear passes through the target square and as close as possible to 15 bees without going over. Represented solution as a flowchart.


### Part 2:


Wrote code to perform some simple calculations and test board functions. This was the first lab completed after circuit assembly.
