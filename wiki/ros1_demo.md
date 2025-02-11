# Docker for ROS1 System - Simulation and Path Planning Demo

[Link](https://drive.google.com/drive/folders/1yzJbm0I91lRBJCyyGA6qIhRGd1CaO-Fl?usp=drive_link) to the image on Google Drive

For more info about Docker (optional), visit the guide in the [Docker section](wiki/docker.md)


## Install Docker 

```
curl -fsSL https://get.docker.com -o get-docker.sh
sudo sh ./get-docker.sh 
```

## Load and run the image 
Run the bash file provided to run
```
source run_image.sh
```

You will see the a window of Gazebo (our Simulation software) and another window for RViz (our Data Visualiser for Path Planning)


<p align="center">
  <img height="500" alt="Gazebo RViz" src="image/sim_path_planning_demo.png">
</p>


## How to see the code for Simulation
You can stop the two containers that run the Simulation and Path Planning and view the code:

```
docker stop utsma_demo_path_planning
docker stop utsma_demo_sim
```

Install VSCode (if you haven't) in your host machine (outside the container, on the operating system of your computer). For Linux:
 
```
sudo snap install --classic code
```

Install an extension to view and edit code inside containers  
```
code --install-extension ms-vscode-remote.remote-containers
```
Follow [this](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) to attach to the running container `utsma_demo_code_viewer`

Then navigate to the code directory. Inside VSCode, File/Open Folder..., go to this path `/utsma_ws/src/`


## Quick navigation

The code regarding Simulation can be found in the following directories:

 - `utsma_description` this has the car 3D model, including URDF and mesh files (URDF - Unified Robot Description Format is a file format for specifying the geometry and organization of robots in ROS). There are also some mesh files of environment models and configurations files

 - `utsma_gazebo` this conventionallly contains all the files relative to the Gazebo Simulation, including launch files and world files 

 - `eufs_gazebo_plugin` plugins that helps customise the interaction of our car to the simulation environment as well as other nodes in the system. Since the car is a customised robot model, it requires this module to interact with Gazebo

