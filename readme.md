# ur3_chip_moveit_config

## Overview
This package is for customized ur3 robot. it has the following components:
- UR3 body
- Ensenso camera
- Chip gripper
- Robotiq FT 300

![ ](https://github.com/birlrobotics/ur3_chip_moveit_config/blob/master/pictures/customized_ur3.png  "ur3_robot_with_camera_ftSensor")

## Demo: Run in simulation
```
roslaunch ur_gazebo ur3_chip.launch

roslaunch ur3_chip_moveit_config ur3_moveit_planning_execution.launch sim:=true 

roslaunch ur3_chip_moveit_config moveit_rviz.launch config:=true

```
## Demo: Run in reality
Refer to [link](https://github.com/birlrobotics/birl_ur5_assembly_experiment) 