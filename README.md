Husky_Sawyer_MoveIt_Config
==========================

This package contains the MoveIt configuration to use the Rethink Robotics arm Sawyer with the Clearpath Robotics Husky ground vehicle.

To use this package, install the following into your catkin workspace and catkin make

 - cd ~/catkin_ws/src/
 - git clone https://github.com/johodges/sawyer_gazebo
 - git clone https://github.com/RethinkRobotics/sawyer_robot
 - git clone https://github.com/RethinkRobotics/intera_sdk
 - git clone https://github.com/RethinkRobotics/intera_common
 - git clone https://github.com/RethinkRobotics/sawyer_moveit
 - git clone https://github.com/johodges/husky_sawyer_moveit_config
 - cd ~/catkin_ws && catkin_make

To run the Husky with the Sawyer arm

 - roslaunch sawyer_gazebo playpen_husky.launch
