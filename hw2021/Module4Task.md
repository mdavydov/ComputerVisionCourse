# Tasks for Module 4

## Task 1. Solve task 1A or 1B at your own choice

  ### Task 1A. Finding ellipses

  (20%) 1A.1. Implement algorithm for finding ellipses using 5, 6, and 7 points;
  
  (20%) 1A.2. Compare how stable are these 3 algorithms to displacement of point locations 
   - Create experiment where points are randomly taken on the ellipse edge
   - Suppose normally distributed error in point locations N(0, &sigma;<sup>2</sup>)
   - Propose and substantiate some metric for ellipse displacement
   - Draw plot X: &sigma; &in; [0,10] Y: mean and deviation of ellipse displacement using 5,6,7-point algorithms
   - Here is an [Example](../images/plot.jpg) of mean and deviation plot
   - Make at least 100 attempts for every &sigma;

  ### Task 1B. Fix distortions in photos using straight lines
   
  (20%) 1B.1 Rewrite TensorFlowCameraModel.ipynb to take into account weights of the points
  
  (10%) 1B.2 Find minimal set of required points to fix distortions in the example
  
  (10%) 1B.3 Add tangental distortion (p<sub>1</sub>, p<sub>2</sub>) parameters to the model. Estimate how stable is the algorithms with tangental distortion parameters

## Task 2. 3D Reconstruction

 2.1 Implement or use existing 8-point algorithm for finding fundamental matrices
 
 2.2 Take 3 photos of UCU building (or some other building) with your smartphone
 
   - Do not use Google Maps because they are pseudo-3d
 
 2.3 Undistort images if straight lines are not straight in the photo
 
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
