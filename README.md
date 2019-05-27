# Computer Vision Course

## Module 1. Image processing basics. Local image processing and feature descriptors
- image acquisition: cameras and depth sensors
- Color spaces:
 [HSL and HSV](https://en.wikipedia.org/wiki/HSL_and_HSV),
 [L\*a\*b\*](https://en.wikipedia.org/wiki/Lab_color_space),
 [sRGB](https://en.wikipedia.org/wiki/SRGB),
 [CIE XYZ](https://en.wikipedia.org/wiki/CIE_1931_color_space),
 [Display P3](https://en.wikipedia.org/wiki/DCI-P3#Display_P3)
- Image degradations: noise, blur, highlights and shadows
- Local features. Scale, rotation, affine transformation, exposition invariant
- Denoise and deblur
- Image pyramids
- Finding lines, circles, ellipses
- Good Features To Track
- Harris Detector, FAST Feature Detector
- Scale Invariant and Affine Invariant Detection
- SIFT Descriptor
- Local Binary Pattern (LBP) Descriptor
- Feature stability
- Neural nets for feature extraction

## Module 2. Image Segmentation and Correspondence
- Segmentation and Correspondence problems
- Graph Cuts for Image segmentation
- Energy minimization
- Random Markov Fields
- Stereo correspondence, homography
- RANSAC
- Dynamic programming
- Optical Flow: Horn Schunck, Lucas-Kanade/KLT
- Optical Flow and 3D trajectories
- DPM: Deformable Part Models
- Graph Cuts in 3D
- Layered motion
- Background models
- Neural nets for image segmentation and correspondence

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

- 3D space basics
- Camera calibration
- Location from motion estimators
- Matchmoving
- Finding planes
- Geometry estimation from textures
- Triangulation
- 3D object reconstruction
- Camera tracking
- Reconstruction from several cameras
- Geometry-based AR
- Light and materials
- Shared AR Experiences
- Successful AR samples
- Neural nets for AR and 3D reconstruction

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

