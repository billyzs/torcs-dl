# torcs-dl

Racing simulation, motion planning, deep learning. We're all about speed.


# Introcudtion

A lot of research has been done on autonomous driveing for non-holonomic 4 wheeled vehicles in unrban environments. But we're proposing a different formulation of the probelm by taking it to the race tracks, where there are no pedestrains, bicycles sharing the road with race cars. We propose the investigatoin of path planning algorithms for autonomous competitive driving, where we optimize for speed, competitiveness (measured in terms of the ability do do aggressive and/or defensive driving based on changing circumstances), ability to adapt to varing road surface conditions, and successful completion of race without accidents.

# Installatoin
Tested on Ubuntu 14.04 and Mint 18 Sarah (Ubuntu 16.04)

## Requirements
1. [My fork](https://github.com/billyzs/gym_torcs) of Gym-TORCS developed by [ugo-nama-kun](https://github.com/ugo-nama-kun). I fixed a few places that failed compilation of `vtorcs-rgb`. Follow the instruction in README to install all its dependencies too. You may want to do it in an virtualenv. 

# Report
[Race condition: Design of a Path Planning Algorithm for Autonomous Competitive Driving](https://www.overleaf.com/read/rwhbjydhhhvf#/27885219/)
