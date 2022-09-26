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
`launch navvis_description navvis_description.launch`
2. View the robot model without Joint_state_publisher GUI:
roslaunch navvis_description navvis_description.launch use_gui:=false
