# Tasks for Module 4

## Note: you can use 3-rd party libraries for visualisation of the results, feature extraction, finding matches, camera calibrartion, solving equations, performing SVD decomposition. All other computations should be made directly with matrices. You can use examples from the lecture as templates. You can use methods from 3-rd party libraries to verify your results.

## (30%) Task 1. Camera calibration
  
 1.1 Print pattern for camera calibrartion. Take 8-10 photos of it and find distortion coefficients and camera calibration matrix using OpenCV.
  
 1.2 Take a photo of a rectangular object. Find camera calibration matrix and distortion coeficient using straightness maximization and the example from the lecture (https://colab.research.google.com/drive/1rRoRtHkbJC9rDO3Ve_6Impagz8i_s_-D?usp=sharing).
  
 1.3 Compare results from 1.1 and 1.2 and write a conclusion. Choose which camera calibrartion matrix to use.

## (30%) Task 2. Fundamental matrices and epipolar lines

 2.1 Take 2 photos of UCU building (or some other building) with your smartphone. Undistort them.
 
 2.2 Choose 8 matching points liying on the same plane (for example the front plane of the building). Find fundamental matrix and visualize epipolar lines and epipoles using this set of points.
 
 2.3 Choose 8 matching points NOT liying on the same plane (take them from different sides of building, for example 4 from one side and 4 from another). Find fundamental matrix and visualize epipolar lines and epipoles using this set of points.
 
 2.4 Find essential matrix using 5-point method. Calculate fundamental matrix using essential matrix and camera calibration matrices. Visualize epipolar lines and epipoles using this method

 2.5 Compare results from 2.2-2.4 and write a conclusion. Choose which fundamental matrix to use
 
 
## (40%) Task 3. 3D reconstruction using 2-view SfM
 
 Reconstruct 3D shape of the building using 2-view SfM method. Create 360-degree animation to visualize the result.
 
## (+30%) Task 4 (for extra points) 3D reconstruction using N-projection SfM

 Take 4 photos of the building and reconstruct 3D shape of the building using N-view SfM method. Imply restrictions on projection matrices. Create 360-degree animation to visualize the result.
 
All tasks should be implemented in Python/Colab with sufficient comments
