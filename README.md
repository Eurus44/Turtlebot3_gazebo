How to run.
1. Add file `midterm_turtlebot3_world.launch` to catkin_ws `catkin_ws/src/turtlebot3_simulations/turtlebot3_gazebo`
2. Open terminal
3. cd catkin_ws
4. Run `catkin_make`
5. Run `source devel/setup.bash`
6. Run `roslaunch turtlebot3_gazebo midterm_turtlebot3_world.launch`
7. Open other terminal
8. Run `roslaunch turtlebot3_navigation turtlebot3_navigation.launch map_file:=$HOME/map.yaml`
9. Select endpoint and let's see robots find out the way to goal.
	
	

