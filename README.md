#move_base_goals for ROS noetic

-[This is a solution to navigate the turtlebot3 around the Gazebo world set, done in ROS version noetic!]
-[Distributor ID:	Ubuntu,	Description:	Ubuntu 20.04.3 LTS,	Release:	20.04,	Codename:	focal]
	
##Turtlebot3_gazebo
-[First unzip the file catkin_ws in the directory /home/user/ (it can be named as any folder name you want!)]

##Open a terminal and execute this

~$ cd ~/catkin_ws 	# Navigate to the catkin_ws or the "name of the directory"

~$ catkin_make		# build the catkin

-[Then launch the file name move_base_assignment.launch]
#simply execute this in terminal
~$ roslaunch move_base_goals move_base_assignment.launch

-[And here you go with the results! ]

turtlebot3_gazebo world(maze) will be launched and then the R.VIZ navigation will be launched and then you can see the turtlebot3 moving around avoiding obstacles.


I have placed the lauch file in the directory /catkin_ws/src/move_base_goals/launch/
The c++ executable file is placed in the directory /catkin_ws/src/move_base_goals/src/
#Author --> thyman_bathlo@yahoo.com



