# RoboND-Localization-Project

This is the sixth project of the Robotics Software Engineering Nanodegree. A first example how-to design a robot in ROS is made. It is called udacity_bot and consists of a rectangular box chassis with two wheels and two castors running on differential drive. Another urdf file is designed from scratch to contain the physical specs of a robot called mazebot with a spherical chassis and three wheels with the two back wheels running on differential drive. The urdf folder corresponding to each robot contains the .xacro file that lists each robot's physical specifications and RViz visualization while the .gazebo file configures the robot to run in the Gazebo environment. 

The goal of this project is to set sensor, planner, costmap, and AMCL parameters so that the global localization problem can be solved and each robot can successfully navigate from a start position to its end position. The config file for each robot contains the tuned planner and costmap parameters. The launch folder contains amcl.launch which configures the parameters for the adapted Monte Carlo localization algorithm. The jackal_race world is the environment that the robots navigate in and navigation_goal.cpp in the src folder is the file that launches the goal location telling the robot where to end. 
