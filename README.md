This repository contains additional material for the paper [1]:

- The file "video_demo.gif" contains a video demonstration that illustrates how the edge service in Open RAN performs the trajectory prediction of the objects detected by the CARLA clients, based on a particle filter (PF). This is observed on the left, where the trajectory predictions appear in real time. The particles used for trajectory estimation are the "cloud" of points, the trajectory estimations (stars), and the ground truth (circles). Each color represents a different object. On the right we can see the weights associated to the particles of the PF associated to each trajectory. Recall that the trajectories are estimated by performing the weighted average of the PF particles. 

- The file "additional_material_PF" contains further details of the particle filter used for the edge service.

[1] J. Serra, A. Aguilar, E. Abu-Helalah R. Parada P. Dini "Multi-Object Tracking for collision avoidance using multiple cameras in Open RAN Networks" submitted to IEEE ICMLCN 2025.
