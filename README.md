## Dependencies
ROS Desktop Full  
PX4 Firmware  
MAVROS  

## Compiling & Running
Make sure all dependencies are installed  
Create a workspace  
Fork project so files are in your workspace  

cd your-workspace  
catkin_make  
source devel/setup.bash  
./launch-offb.sh  

##  To Do  
Smooth out flight (i.e. change theta as x y and z changes)  
Add obstacle avoidance  
Add path planning  
Modify gazebo world file to be similar to IARC course (i.e. add the two goal posts we have to fly around and the swaying mast)  
Create folder and file for gazebo world and upload to github (right now it runs using a world file that is part of the PX4 Firmware)  
After takeoff program the VTOL to fly around the two goal posts for a set length