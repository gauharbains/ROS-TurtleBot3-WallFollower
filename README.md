# ROS-TurtleBot3-WallFollower

This repository consists of the `wall_follower` ROS package. It enables the TurtleBot3 robot to autonomously find its way out of a given maze. The maze to be solved is shown below in figure. It is given that all the walls in the maze are connected and the goal point is located at the periphery. In addition to this, there are some obstacles that are present in the center of the maze and along the walls.



## Compile and Run 

```
1. Please paste this package in the 'src' directory of your catkin workspace and run `catkin_make`
2. Run `rospack profile`
3. Launch the gazebo maze environment using --> roslaunch maze maze.launch
4. Run the maze_solver.py node from the package `wall_follower` using ----> rosrun wall_follower maze_solver.py 
5. The program exits after the robot exits the maze.
```    
    

<img width="530" alt="maze1" src="https://user-images.githubusercontent.com/48079888/93161689-0cbcdd80-f6e1-11ea-9ea1-279541866914.PNG">
