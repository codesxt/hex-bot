# Hex Bot
Hexapod robot implemented in ROS.
This project consists in the following packages:
* hex_bot_description: definition of the robot
* hex_bot_control: variables to control the robot
* hex_bot_gazebo: configurations to simulate the robot in Gazebo
Generating the URDF:
```
rosrun xacro xacro.py `rospack find hex_bot_description`/urdf/hex_bot.xacro > `rospack find hex_bot_description`/urdf/hex_bot.urdf
```
