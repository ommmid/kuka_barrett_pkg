# kuka_barrett_pkg
Barrett Hand (282) is attached to arm Kuka (LBR iiwa 14Kg) as the gripper to make kuka_barrett robot. This repository contains several packages:  
kuka_barrett_description package in which all the needed files are imported from Barret Hand and Kuka packages and modefied so that it does not depend on any other packages. Running the launch file wil run the rviz too with which the user can see the robot and move the joints with the slider from the gui.   
kuka_barrett_control package is to have the robot in gazebo and be able to work with ros controllers.  
kuka_barrett contains a node (joint_controller.cpp) to show how to move the joints in gazebo using std_msgs/Float64 and trajectory_msgs/JointTrajectory.
