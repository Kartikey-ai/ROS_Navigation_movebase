# ROS_Navigation_move_base
Ros has an inbuilt navigation planner which is move base. so here the code is to determine how to use it and hep in navigating of the bot.

### Gmapping
This code also uses gmapping as a SLAM technique to identify the bot's location and the map around it. Hence use all the details to find the best path  to its goal.
You can use 2d Nav goal in Rviz to define the goal point in rviz.

### Description
Bot description can be used from urdf_teleop updated in another repository.
Launch that urdf file in the desired environment (world file) and then use it to navigate the bot.

### Commands
roslaunch navigation_ros move_base.launch
