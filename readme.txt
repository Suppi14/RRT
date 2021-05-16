Rapidly Exploring Random Trees (RRTs)

We consider a robot in a 2D environment represented by a grid map. Our objective is to find a path
between a start cell and a goal cell. RRT is used to find a possible path for the robot without colliding with the obstacles.

Execution steps:

1. Execute the RRT.py file in python 2
2. The initial position and the goal position can be changed in the main function along with the other parameteres 
   such as no. of iterations, radius of the obstacle, delta etc.
3. The grid map contains the entire 2D environment.
4. In the map '1' represents an obstacle and '0' represents free space.
5. Incase there is a 'key error for the goal position', that indicates that the no. of iterations has to be increased to a higher number 
   inorder for it to reach the goal. i.e. (Start node and goal node are too far away)
6. For example see plots attached for different parameters :
    1. init_node = (6,7), goal_node = (34,30), iterations = 2500 - fig1
    2. init_node = (2,4), goal_node = (34,38), iterations = 5000 - fig2
    3. init_node = (3,3), goal_node = (11,15), iterations = 400 -  fig3
