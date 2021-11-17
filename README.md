# 3D-Imaging-using-Stereo-Matching
3D mapping and depth mapping of environments using stereo cameras.

The framework used first
obtains depth and disparity maps through algorithms like Census Transform(CT) as well as Sum
of Absolute Difference(SAD) Algorithm to implement block matching. These disparity maps are
then converted into point clouds using Open3D. The results obtained from the different methods
are also observed, compared, and the results are shown. These algorithms are first tested on stereo
datasets before being implemented in the Gazebo simulation environment. A novel method is also
proposed which reduces the errors when compared with the existing algorithms. In contrast to common existing methods used to calculate disparity
maps, we have used Multi-Block Matching along with SAD and CT to perform block matching.
This reduces the bad error when compared with the ground truth.

This project was done for Image and Video Processing Course from Jan-May 2021.

Project Members:

Roshan Rangarajan

Saikumar Dande

Chandravaran Kunjeti
