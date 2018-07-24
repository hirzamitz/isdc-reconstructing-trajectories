# isdc-reconstructing-trajectories
ISDC Project - Reconstruct Trajectories using Python

In this project, I've taken raw sensor data that includes the timestamp, displacement, yaw_rate and acceleration and converted it into plots of vehicle trajectories.

This project includes the following files:
1. helpers.py - Contains helper function for loading the raw input data.
2. reconstructing trajectories.ipynb - Jupyter notebook that contains all the instructions for the project
3. trajectory_1.pickle - Contains the raw input data for a three quarter turn trajectory 
4. trajectory_2.pickle - Contains the raw input data for a merge trajectory
5. trajectory_3.pickle - Contains the raw input data for a parallel park trajectory
6. trajectory_example.pickle - Contains the raw input data for a vehicle that accelerates forward then turns right until it almost completes a full circle turn
7. testing.py - Contains code for testing get_speeds, get_x_y and get_headings
