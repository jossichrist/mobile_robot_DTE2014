# mobile_robot_DTE2014
this github will be included models and controller mobile robot using ROS + GAZEBO

author : Josua Christanto/ DTE2014

How to use models:
1. install Gazebo 7 and Ros Kinetic
2. copy camera, my_robot, pioneer2 folders to .gazebo/models
3. open gazebo - insert - my_robot


Tutorial how to run mobile robot simulation part 1

1. open terminal, go to my_first_mobile folder
2. 1st tab : "source devel/setup.bash" and then "roscore"
3. 2nd tab : "source devel/setup.bash" and then roslaunch diff_wheeled_robot_gazebo diff_wheeled_gazebo_full.launch"
4. 3rd tab : "source devel/setup.bash" and then roslaunch diff_wheeled_robot_control keyboard_teleop.launch"

NB : if bad error happens, repeat from 2nd command (devel/setup)

5. try moving the robot using this instructions !
Control Your Turtlebot!

Moving around (Press from your keyboard):
-   u   i   o
-   j   k   l
-   m   ,   .

- q/z : increase/decrease max speeds by 10%
- w/x : increase/decrease only linear speed by 10%
- e/c : increase/decrease only angular speed by 10%
- space key, k : force stop
- anything else : stop smoothly

