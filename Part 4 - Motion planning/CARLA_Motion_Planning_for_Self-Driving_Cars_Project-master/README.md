# CARLA_Motion_Planning_for_Self-Driving_Cars_Project

This project is a part of the Self-Driving Cars Specialization course in Coursera. The detail about this specialization can be found [here](https://www.coursera.org/specializations/self-driving-cars).

The performance of the motion planner was simulated using the CARLA simulator, which is a modified version of the original CARLA simulator 
with additional maps included. If you wish to try my controller yourself, please download and install this simulator following the 
instructions [here](https://www.coursera.org/learn/motion-planning-self-driving-cars/supplement/i9R3x/carla-installation-guide). To learn 
how to use this simulator, you can refer to the project instruction from Coursera 
website [here](https://www.coursera.org/learn/motion-planning-self-driving-cars/programming/wiGwg/course-4-final-project).

To design a reliable motion planner, I implemented behavioral planning logic, as well as static collision checking, path selection, and velocity profile generation.
The files named "behavioural_planner.py", "collision_checker.py", "local_planner.py", "path_optimizer.py", and "velocity_planner.py" contains
these 5 main aspects of the planner.

The screen recording of the simulation for an autonomous driving scenario in a small town can be viewed in YouTube: https://www.youtube.com/watch?v=Mmpbg4ztdn8