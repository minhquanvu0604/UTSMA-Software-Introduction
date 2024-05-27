## Introduction
### Who am I?
My name is James Chivers. I am a new software developer on the UTS Motorsports Autonomous team, currently with a focus on code performance and optimisation. I study Computer Science.

### Why is my role important?
Achieving performant and efficient code in an environment such as autonomous driving is crucial to the project's success. With efficient computation, data can be processed more often and more accurately, and flexibility for balancing systems between performance and energy efficiency is significantly increased. Achieving a good balance of both of these aspects is crucial when running a self-contained system such as an autonomous car, as it is vital for the car to make the most of the limited energy supply it has. The less energy its computers require, the more energy can be diverted to its driveline, and the longer it can run.

### What are my goals?
During the 2024 UTSMA Design Challenge, I would like to dedicate my time to achieving two main tasks. These are re-implementing the car path planner to use OpenCL, a framework for implementing highly parallel algorithms to run on specialised hardware such as graphics procussing units, and creating a ROS2 interface with our IMU (Inertial Measurement Unit).

## Task List
### OpenCL Path Planner
- Establish a development toolchain for working with OpenCL
- Implement Delauney Triangulation Path Planning using OpenCL
- Create a suite of accuracy and performance tests to compare the OpenCL implementation with the existing single-thread CPU implementation
- Tweak and optimise OpenCL task dispatch to most effectively utilise the available hardware

### IMU ROS2 Driver
- Create a ROS1 environment to test the IMU device with official drivers
- Create a ROS2 environment to test the IMU device with (unmaintained) third-party drivers if possible
- Compare results between official and unmaintained, and compile a data set for testing
- Create a new ROS2 Humble module and implement a device-driver-to-ROS-topic data interface to publish data to the ROS2 messaging system for other services to utilise.

### Collaboration
- Collaborate with Quan for testing and implementing the OpenCL DTPlanner

## Project Timeline
I intend to dedicate 15-20 hours per week working on these tasks, beginning after Monday 3rd of June.