## Environment

Urban challenging terrain, indoor and outdoor, defense/military scenario, e.g. multi-floor buildings with stairs, warehouses, industrial spaces, etc. possibly damaged by exposion

## Manouvers

* moving up/down stairs
* climbing up/down largre obstacle
* traversing large gap
* crawling under obstacle

(all a

with manipulator force control
* door opening
* pushing object

## Inputs

* goal pose (e.g. a pose selected on map)
* current state estiamtion of robot
* current map

## Modules

* Perception: elevation map generation
* Higher level navigation module - is planning intermediate poses (possibly with velocities)
* Lover level locomotion module - is planning direct command to robot actuators

## Algorithms

* Reinforcement learning, in particular hierarchical reinforcement learning, possibly with expert demonstration
* Perception algorithms to generate map

## Sim-to-real

* building simulationn environment with ability to genereate diverse scenarios
* training in simulation in large scale
* building real environment (e.g. safety belts)
* sim-to-real transfer

## PIAP robot: [PIAP gryf](https://www.antyterroryzm.com/portfolio-posts/robot-piap-gryf/)

* [PIAP GRYF - extreme mobility](https://www.youtube.com/watch?v=rxESGyILEos)

## Examples from [Robotic Systems Lab - Legged Robotics at ETH Zürich](https://rsl.ethz.ch/)

* [ANYmal Parkour: Learning Agile Navigation for Quadrupedal Robots](https://sites.google.com/leggedrobotics.com/agile-navigation)

![local planning](Screenshot%20from%202024-05-20%2010-13-36.png)


* [Learning robust autonomous navigation and locomotion for wheeled-legged robots](https://junja94.github.io/learning_robust_autonomous_navigation_and_locomotion_for_wheeled_legged_robots/)

![local planning](Screenshot%20from%202024-05-20%2010-16-01.png)

![complex obstacle](Screenshot%20from%202024-05-20%2009-13-40.png)
