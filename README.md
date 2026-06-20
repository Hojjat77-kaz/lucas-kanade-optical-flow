# Lucas-Kanade Optical Flow

A computer vision project that demonstrates sparse optical flow using the Lucas-Kanade algorithm in OpenCV.

## Project Overview

This project tracks feature points across video frames and visualizes their motion using motion vectors.

The implementation includes:

* Feature detection using `goodFeaturesToTrack`
* Sparse Optical Flow using `calcOpticalFlowPyrLK`
* Motion vector visualization
* Feature point re-detection
* Trajectory tracking

## Concepts Covered

* Feature Detection
* Corner Detection
* Lucas-Kanade Optical Flow
* Image Pyramids
* Motion Estimation
* Motion Vectors
* Object Tracking Fundamentals

## Technologies

* Python
* OpenCV
* NumPy

## Pipeline

1. Read first video frame
2. Convert frame to grayscale
3. Detect good feature points
4. Compute optical flow between frames
5. Filter successfully tracked points
6. Draw motion vectors
7. Update tracked points
8. Re-detect features when necessary

## Example Output

The algorithm tracks feature points and visualizes their movement with lines representing motion vectors.

## Future Improvements

* Dense Optical Flow
* Vehicle Tracking
* Pedestrian Tracking
* Kalman Filter Integration
* Multi-Object Tracking
* Optical Flow Speed Estimation

## Learning Objectives

This project was built to understand:

* How Lucas-Kanade Optical Flow works
* How feature tracking differs from object detection
* Motion estimation in video sequences
* Practical computer vision tracking pipelines
