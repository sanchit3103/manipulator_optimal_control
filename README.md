# Optimal control of a 2 DOF manipulator to catch a moving ball

<p align="justify">
This project focuses on designing an optimal control problem for a 2 DOF robotic manipulator to catch a moving ball. The robot is modelled using the Peter Corke robotics toolbox in Python. The robot is at rest at (0.5, 0)m at t = 0. A ball is launched with velocity (-2, 0) m/s towards the arm and the robot has to catch the ball at position (0.5, 1)m at t = 1 sec. After catching the ball, the robot will decelerate the ball and land at the resting position of (-1, 0.5)m at t = 2 sec. This optimal control problem is formulated and solved using Scipy's optimization solver to minimize the given loss function. 
</p>

## Project implementation in form of GIF file

<p align="justify">
The GIF below shows the implementation of the optimal control problem to catch a moving ball.
  
</p>

<p align="center">
  
  <img src = "https://github.com/sanchit3103/manipulator_optimal_control/assets/4907348/a006cbda-0871-4d8c-a36b-d220bb109726" height="400"/>

</p>

## Details to run the code

* <b> main.ipynb: </b> Notebook which includes the formulation of optimal control problem, optimization solver and all the plots.
