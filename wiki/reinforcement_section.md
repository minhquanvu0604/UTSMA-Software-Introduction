## Background

UTSMA has a track extraction module and a control system that navigates the car through that track. 

According to plan, we will have a control system that involves a fair extend of dynamics. However, the real dynamics of the car is much complicated than that - think of how many mechanical components like tire, suspension, etc will play a role in deriving the motion of the car.

In light of that, one possible improvement is to apply reinforcement learning (RL) to adapt to this variation. For example, 
in the first lap, the control system may perform poorly, so we improve it by the subsequent laps. So we can achieve that, RL helps to find a strategy to fine tune the control signal.

Aside from that direction, feel free to explore any applications of RL to our system.

## Projects

### Exploration
* What component of the autonomous system can benefit from RL?
  * Adapting capability
  * etc
* Research in topics relevant to racecar, autonomous car, or autonomous robots in general. How RL has been used to solve existing problems in robotics?
* What are the required hardware and software to facilitate RL?
  * Do we need a localisation system to check the ground truth position of the car? If we do it on the sim this can be easily obtained. 
* Any other items you can think of


### Exploring data-acquisition-loop

Link...

A well-made package from Mitchell Rosser. 

#### Questions:
* Does the model regard to control or vision? (We may only need the control one)
* What RL/DL method is used?
* Does it involve end-to-end learning, or there are some guidlines for learning?

#### TASK 1: Explore the components of the package



## Resources 