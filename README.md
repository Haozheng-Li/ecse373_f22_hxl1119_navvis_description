# ecse373_f22_hxl1119_navvis_description

# Laboratory#2a

This repo is a ROS package that contain a basic robot model. 
Dependency:
1. ROS Neotic
2. ROS joint-state-publisher-gui
3. gazebo-plugins
4. ROS velodyne-description

## Quick comnand for view the robot model:
1. View the robot model using Joint_state_publisher GUI:

`roslaunch navvis_description navvis_description.launch`

2. View the robot model without Joint_state_publisher GUI:

`roslaunch navvis_description navvis_description.launch use_gui:=false` 

The parameter `use_xacro` can be used to decide that viewing the robot model using URDF file or XACRO file.
ex:

Command for viewing the robot model using XACRO file with joint_state_publisher GUI:

`roslaunch navvis_description navvis_description.launch use_xacro:=true`

Besides, the parameter use_robot_state_publisher` can be used to decide to start robot_state publisher which takes information about joints and
creates transforms published on the /tf and /tf_static topics or not.

Command for viewing the robot model robot_state_publisher:

`roslaunch navvis_description navvis_description.launch use_robot_state_publisher:=true`

