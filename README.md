# hector-slam-rover

sudo chmod a+rw /dev/ttyACM0 

roslaunch gproject lidar.launch

roslaunch hector_slam tutorial.launch

rosrun map_server map_saver -f ~/ros/catkin_ws/src/gproject/worlds/home1
up to this point i can map and control the robot



agiaaaaaaan 

roslaunch gproject lidar.launch

give permission to adom transformer script and all other scripts 

roslaunch gproject odomtransformer.launch

roslaunch gproject localize.launch

rosrun gproject movement.py 


missing gripper and the testing of qr code with gripper

without reaching the movement.py step i can try the robot movement in rviz and see how good it is point itin some directions 

and then try to fix the localize file for best thing possible 


the arduino file is only cmd i need to fix arduino file in package to have same connection as mode 4 of cars 
