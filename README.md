- We will use TurtleBot3 world for the map creation , and gazeboo for simulation.

export TURTLEBOT3_MODEL=waffle

roslaunch turtlebot3_gazebo turtlebot3_world.launch

- Running navigation mode using the following commands in a new terminal:

export TURTLEBOT3_MODEL=waffle

roslaunch turtlebot3_navigation turtlebot3_navigation.launch map_file:=$HOME/map.yaml

- Estimating the initial pose using 2D Pos Estimating and  2D Nav goal buttons in the Rviz menu, to direct it in the map using the arrows

- ![Screenshot from 2021-08-20 03-25-42 - 1](https://user-images.githubusercontent.com/85526390/130160739-ae59bef6-714d-4c86-ae8c-575d1c781c15.png)
. 

