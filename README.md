# Intel RealSense Gazebo ROS plugin

This package is a Gazebo ROS plugin for the Intel D435 realsense camera. This repository is a fork of the [issaiass/realsense_gazebo_plugin repository](https://github.com/issaiass/realsense_gazebo_plugin).
 
## Installation

Run the following commands to install this plugin:
```
# Make a catkin workspace.
mkdir -p ~/catkin_ws/src
cd ~/catkin_ws/src

# Clone the repository.
git clone https://github.com/troiwill/realsense_gazebo_plugin.git

# Build
cd ../
catkin build
```

Now, you should be able to use Intel Realsense cameras in Gazebo!
