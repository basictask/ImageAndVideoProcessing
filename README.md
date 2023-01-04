# Image and Video Processing
This repository contains various algorithms used for several different aspects of processing photometric data.

0. Median Filter: remove people from a continuous video feed producing a single image.

1. Prewitt edge detector: gradient filter és nonmaxima-suppression (NMS)
Output is two images: 1. gradient magnitute; 2. final result after NMS.

2. Thresholding algorithm by Otsu
Output: thresholded image and obtained threshold value.

3. Detection of circular object by edge detection and Hough transform for circles
Input: 1. image containing circular objects, e.g., cells; 2. range of diameters. Output: 1. accumulator image; 2. input image with objects detected in given range of diameters.

4. Motion tracking of feature points and dense optical flow
Input: 1. short video sequence; 2. maximum displacement.
Output: 1. points tracked in the video sequence (for both test sequences); 2. optical flow of the sequence (for motor sequence only).
