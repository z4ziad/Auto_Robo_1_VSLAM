This repo explains how to start Isaac ROS VSLAM in Docker 
after installing and running Isaac ROS Object Detection and Object 
Tracking on Assignment 8 in Autonomous Robotics I.

# Assumptions
* You completed Assingmnet 8 with Object Tracking in Docker on Jetson Orin Nano.
# Install Required VSLAM Assets
1. Start the `isaac_ros_dev-aarch64-container` 
```shell
$ docker start -a -i isaac_ros_dev-aarch64-container
