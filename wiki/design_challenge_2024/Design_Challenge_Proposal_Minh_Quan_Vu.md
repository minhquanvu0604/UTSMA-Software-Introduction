
# Design Challenge Proposal 

## Introduction
My name is Quan, Minh Quan Vu. I am a Software Technical Director for UTS Motorsports Autonomous. I am responsible for the technical 
and management aspects of the high-level control system, or Software in short. The high-level control section can be distinguished as the brain of the autonomous driving system, in constrast the hands, which is the Embedded section that we work closely with.

When it comes to sensors/perception, there is fine line between Software and Embedded. Software focus is in the depth camera system, which involves object detection in traditional and deep-learning-based methods. Meanwhile, Embedded is working on GPS, encoders which involves more hardware interfacing, digital signal processing. 

Software is typically deployed on top of a working Mechanical, Electrical and Embedded system. In light of that, one of the most important motivations for the Design Challenge is to create a test bed for Software to assemble all of our components. While integration can happen in the simulation, the complete physical robot is beneficial to solidify understanding, allows any problems such as faulty assumption made along the way to be diagnosed and analysed.

Other motivations can be found here...

## Task List

### Computer Vision
- Integrate in to a complete ROS 2 node.
- Test the accuracy, stability of depth information.

### Integration
- Gather all the bullets points to research on the capability of ROS 2 in process management: node lifecyle, heartbeat, parameter server, etc.
- Deploy on a Jetson.
- Dockerise all the development and deployment environments.
- Integrate all software components in the last week.

### Section Collaboration
- Computer Performance: Collaborate with James to improve the path planning algorithm.
- Deep Reinforcement Learning: Discuss with Josh about possibilities to integrate DRL.


## Timeline 
I will work on the above tasks and provide support to Software and Embedded. Minimum time commitment will be 20 hours per week.
In the last week, I will have to do some marking for Programming for Mechatronic System, and will be away in a undefined timeframe, 
since it depends on the time slots students book me for viva.

### Last Week - Testing JAM (10/6 - 16/6)
- PfMS group discussion.
- Git, Documentation with Markdown disscussion.
- Docker group discussion: Software engineering students share their experience and understanding in Docker.

