## Localization Project

This project aims to teach a robot to Localization itself, given a 2D map of an environment. More details about the project can be found in the report here.

### Instructions to run the project

Organize the files in the repo into the following directory structure "catkin_ws/src/udacity_bot/.."

Use ctrl + alt + t to open a terminal and type the following commands :
```
catkin_make
source devel/setup.bash

roslaunch udacity_bot main.launch
```
Open another terminal, and after building the source files and setup script, type
```
rosrun udacity_bot navigation_goal 
```
