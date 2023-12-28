## Hannah - Voice controlled Robotic Manipulator

Software: ROS2 humble 

OS: UBUNTU 22.04 

ROS2 packages used so far:

->ros2_control

Project Description:

  Hannah represents an innovative venture into the realm of voice-controlled robotics, implemented through the powerful ROS2 framework. The initial phase involves meticulous testing of the control logic within the simulated environment of Gazebo.

Present progress:

  - Created urdf for the manipultor ,intergrated them with gazebo
  - Added gazebo,ros2 control tag 

  To review my present progress, clone this git repo and in ,

  Terminal 1 :

         ros2 launch hannahbot_description gazebo_launch.py 
  Terminal 2 :

          ros2 launch hannahbot_controller controller.launch.py 

![image](https://github.com/FERBIN12/Hannah/assets/126778624/1efb453b-26c2-4ce8-b75f-79e0655721d2)
