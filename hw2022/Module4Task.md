# Tasks for Module 4 (draft)

## Task 1. Camera calibration
  
 (20%) 1.1 Print pattern for camera calibrartion. Take 8-10 photos of it and find distortion coefficients and camera calibration matrix using OpenCV.
  
 (20%) 1.2 Take a photo of a rectangular object. Find camera calibration matrix and distortion coeficient using straightness maximization and the example from the lecture (https://colab.research.google.com/drive/1rRoRtHkbJC9rDO3Ve_6Impagz8i_s_-D?usp=sharing).
  
 (10%) 1.3 Compare results from 1.1 and 1.2 and write a conclusion. Choose which camera calibrartion matrix to use.

## Task 2. 3D Reconstruction

 (10%) 2.1 Take 2 photos of UCU building (or some other building) with your smartphone. Undistort them.
 
 (10%) 2.2 Choose 8 matching points liying on the same plane (for example front plane of the building). Find fundamental matrix and visualize epipoles using this set of points.
 
 (10%) 2.3 Choose 8 matching points NOT liying on the same plane (). Find fundamental matrix and visualize epipoles using this set of points.

 
   2.4 Find 8 or more good point pairs on every image pair
   - The points should not lie on the same plane
   - Points should be visible in different views and should not be a visible intersection of disjoint lines
   - Points should represent several faces of the building
 
 (30%) 2.5 Find fundamental matrices for every image pair, draw epipolar lines, find coordinates of epipoles.
 
 (30%) 2.6 Perform and visualize 3D reconstruction of the building using every image pair (so you should get 3 reconstructions)
 
   - Estimate camera calibration matrix and calculate essential matrices to get better results
   - Example of camera calibration matrix estimation  can be found at https://colab.research.google.com/drive/1rRoRtHkbJC9rDO3Ve_6Impagz8i_s_-D?usp=sharing
   - Example of textured output using python/colab can be found at https://colab.research.google.com/drive/1PHHsbQOaV2aS5LoVOgBEh0Htmh0dz51N?usp=sharing)
   - Example of 3D reconstruction can be found at http://programmingcomputervision.com/downloads/ProgrammingComputerVision_CCdraft.pdf, pages 127-143

All tasks should be implemented in Python/Colab with sufficient comments
