# torcs-dl

Racing simulation, motion planning, deep learning. We're all about speed.


# Introcudtion

A lot of research has been done on autonomous driveing for non-holonomic 4 wheeled vehicles in unrban environments. But we're proposing a different formulation of the probelm by taking it to the race tracks, where there are no pedestrains, bicycles sharing the road with race cars. We propose the investigatoin of path planning algorithms for autonomous competitive driving, where we optimize for speed, competitiveness (measured in terms of the ability do do aggressive and/or defensive driving based on changing circumstances), ability to adapt to varing road surface conditions, and successful completion of race without accidents.

# Background

Several other researchers have investigated AI for race autonomous competitive driving [cite]. Motion planning and stability have also been studied from a control engineering perspective, on a open source racing simulator called TORCS. It has a sophisticated physics engine to modle the dynamics of the vehicle and its interaction with the road. It offers the option to fully configure the conditions and parameters of the vehicles and race tracks, and outputs a complete set of data that describes the  state of the vehicle.

# Methodology

We plan to incorporate some form or learning algorithm (deep reinforcement learning, guided policy search, etc.) in the project, while also having more traditional control based motion planners, and compare the performance of each algorithm. Implementation details pending further research.

## Goals
* Implement an algorithm to successfully complete a single race without incident in a single vehicle setting
* Implement higher level behaviors such as taking shortcuts, adapting to road surface conditions in a single vehicle setting
* Implement aggressive driving behavior (have one car in front and overtake that vehicle)
* Implement defensive driving behavior (have one car chasing behind, prevent it from overtaking us)
* Simulate and optimize for actual race with multiple cars.
