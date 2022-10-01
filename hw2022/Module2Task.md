# Tasks for Module 2

1. (15 points) Separate text from background and denoise [(images for task 1)](#textimages).

   The segmentation should make all background white and all text black.
   The algorithm should detect areas with inverted text automatically
3. (15 points) Estimate number of objects [(images for task 2)](#countimages)
   
   You can manually adjust segmentation parameters for each image or have one algorithm and get +5 points

5. (20 points) Separate object from background [(images for task 3)](#objimages)

   Adjust parameters of GrabCut algorithm to get the best result and compare to the result of u2Net-p neural network

7. (20 points) Find projective transformation matrix with 4 point pairs by solving equation with 13 unknowns (H, w_1, w_2, w_3, w_4)  
8. (30 points) Implement (i) or (ii) at your own choice:
   1. Implement Stereo Matching using Dynamic Programming
   2. Implement PatchMatch algorithm

   In both tasks you should visualize obtained optical flow.
   You should not use ready-made implementations or take working code from github or other sources.
   You can downscale images for faster processing.

Test images for stereo matching can be taken from
https://vision.middlebury.edu/stereo/data/scenes2014/zip/![image](https://user-images.githubusercontent.com/1785815/193411903-ecd0ac92-8244-4d62-a91b-7998d5eb21b4.jpeg)


For example:

https://vision.middlebury.edu/stereo/data/scenes2014/zip/Flowers-perfect.zip![image](https://user-images.githubusercontent.com/1785815/193411908-ab7627c8-14e4-4192-a83d-00358b083104.jpeg)

https://vision.middlebury.edu/stereo/data/scenes2014/zip/Couch-perfect.zip

Test images for testing the Patch Match algorithm can be taken from MPI Sintel dataset (http://sintel.is.tue.mpg.de/downloads)

for example

![](images/frame1.jpg)
![](images/frame2.jpg)

**Solutions should be available on colab.research.google.com and shared for access using link only**

## Notes

**In task 4** correctness of solution (up to scalar multiplier) can be verified using cv functions:

```
cv2.getPerspectiveTransform(pts1,pts2)
cv2.warpPerspective(img,M,(w, h))
```

## <a name="textimages"></a> Separate text from background

![](images/text1.jpg)

![](images/text2.jpg)

![](images/text3.jpg)


## <a name="countimages"></a> Estimate number of objects

![](images/count1.jpg)

![](images/count2.jpg)

![](images/count3.jpg)

## <a name="objimages"></a> Separate objects from background

![](images/obj1.jpg)

![](images/obj2.jpg)

![](images/obj3.jpg)






