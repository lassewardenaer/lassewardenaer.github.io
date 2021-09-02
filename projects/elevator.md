---
layout: project
type: project
image: images/elevator.png
title: Elevators to infinity
permalink: projects/elevators
# All dates must be YYYY-MM-DD format!
date: 2021-05-01
labels:
  - Real time programming
  - Elixir
summary: My team developed a system for controlling n elevators over tcp with a high level of fail safe functionality.
---

<img class="ui medium right floated rounded image" src="../images/elevator.png">

In this project we created a system for controlling n elevator using elixir. The system could recover from power loss, loss of internet connection and other faults. The project was focused around solving threading problems, and how to deal with concurrency. 

The system was tested on both a physical representation of elevators running on different hardware and connected through TCP. It was also tested by using a simulation tool which was run in the terminal.

My main task in this project was to design the queuing system and make sure that every order was taken, in case of an error. 

I learned that keeping a system with many concurrent processes free of race conditions can be hard, and that the best solution to most of the problems is to handle them the same way. Also, it is smart to "fail fast", so that one error does not spiral into other ones. 

You can learn more at [the projects github page](https://github.com/lassewardenaer/TTK4145-Sanntidsprogrammering).




