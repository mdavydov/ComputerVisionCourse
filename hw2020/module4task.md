# Module 4 homework

Task 1. (7 points) Finding ellipses

  1.1) (3 points) Implement 5-point and 6-point algorithm for finding ellipses;

  1.2) (4 points) Build plot with 2 functions:
   - (X) maximum deviation of points (0..20 pixels, step = 1),
   - (Y) maximum deviation of ellipse points from the correct ellipse for 5-point method (function 1) and 6-point method (function 2)
   - Make at least 100 attempts for every point of the plot and calculate mean value as a result
   
Task 2. (11 points) 

 2.1 (3 points) Implement 8-point algorithm for finding fundamental matrices
 
 2.2 Take 3 photos of UCU building (or some other building) with your smartphone
 
 2.3 Undistort images if straight lines are not straight in the photo
 
 2.4 (1 point) Find 8 good point pairs on every image pair (the points should not be on the same plane, they should not displace in different views)
 
 2.5 (4 points) Find fundamental matrices for every image pair, draw epipolar lines, find coordinates of epipoles.
 
 2.5 (3 points) Check how the solution of 8-point algorithm will be changed in case of error in point locations (i.e. displace one of the points by 10 pixels, find new solution and compare to original)
 
 Task 3. (3 extra points)
 
3.1 (1 point) Perform 3D reconstruction of the building from task 2

3.2 (1 point) Display 3D reconstructed polygon from different angles of view

3.3. (1 point) Check what kind of ambiguity you have after reconstruction
