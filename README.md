# Computer Vision Course

## Module 1. Image processing basics. Local image processing and feature descriptors

#### Basic image processing: 
- Scale pyramid, bluring,  Image gradients, Contour detection.
#### Correspondences and wide baseline stereo:
- Interest point and distinguished regions detection: 
- Harris operator (corner detection)
- Hessian detector, affine covariant version, Maximally Stable Extrema Regions (MSER).
- Descriptors of measurement regions
- SIFT (scale invariant feature transform), RootSIFT
- Shape context. 
- LBP (local binary patterns)
- Deep learned features (HardNet).
- Deep learned features (R2D2, SuperPoint)
#### Graph neural networks for matching (LoFTR, SuperGlue)
#### Robust model fitting:
- RANSAC.
- Hough transform

#### Other:
- image acquisition: cameras and depth sensors
- Color spaces:
 [HSL and HSV](https://en.wikipedia.org/wiki/HSL_and_HSV),
 [L\*a\*b\*](https://en.wikipedia.org/wiki/Lab_color_space),
 [sRGB](https://en.wikipedia.org/wiki/SRGB),
 [CIE XYZ](https://en.wikipedia.org/wiki/CIE_1931_color_space),
 [Display P3](https://en.wikipedia.org/wiki/DCI-P3#Display_P3)
- Image degradations: noise, blur, highlights and shadows
- Denoise and deblur

## Module 2. Image Segmentation and Correspondence

#### Intro into segmentation, matting and correspondence problems
#### Image segmentation:
-	Level-set methods
-	Otsu thresholding
-	Postprosessing (erosion, dilation, NL-means)
-	Edge-based methods
-	Connected components labeling
-	Active contour model
-	Super-pixel segmentation
-	Watershed segmentation
-	Expectation-maximization in computer vision
-	Gaussian mixture model and K-means
-	Segmentation based on graph cuts
-	Markov models (chain, trees, P2D, CRF)
-	YOLACT
#### Image correspondence:
-	Sparse and dense optical flow
-	Affine and projective transformations
-	Birchfield–Tomasi dissimilarity
-	Dynamic programming for stereo correspondence
-	Polar coordinates and 360 photo
-	Panorama stitching
-	Lukas-Kanade Optical Flow
-	Horn-Schunck optical flow
-	Gunnar-Farneback algorithm
-	PatchMatch algorithm
-	PWC-Net, MaskFlownet


## Module 3. Object Tracking and Search
- Histograms and statistical models
- Hidden Markov Models
- Integral images
- HOG detector
- KLT tracker
- Mean-Shift, CamShift tracker
- Kalman Filter
- Binary features
- Bag of visual words
- minHash
- Image Retrieval for large image collections: image description, indexing, geometric consistency
- Neural nets for object tracking and search

## Module 4. Geometry and Augmented Reality (AR)

- Homogeneous coordinates
- Translation, rotation, scale, and projection matrices
- Camera models
- Rendering 3D scenes
- Camera calibration and removal of lens distortion
- Search for lines, circles and ellipses in photo
- Stereo and epipolar geometry
- Match moving and 3D reconstruction
- Light and materials
- AR examples

## Module 5. Deep Learning for CV

- ML basics: data retrieval, synthesis, augmentation, train and test sets
- Non-deep ML models (PCA, SVM)
- Deep learning
- Different layers. Math and implementation.
- Optimization for size and speed (MobileNet, ... )
- Running in real-time (Core ML 2, etc)
- Study of different architectures: 
Image classification (AlexNet),
Object detection (R-CNN),
Object Tracking (SAE and CNN),
Object segmentation (SegNet),
Instance segmentation (Mask R-CNN),
Optical flow (PWC Net),
Human pose estimation (VNect),
3D reconstruction (LayoutNet),
Transfer-based AR (LSTM Neural nets, GANs).
Metrics learning (face recognition)

