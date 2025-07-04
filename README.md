# 🖼️ Image Processing Practice with OpenCV

This repository contains my daily practice notebooks for learning image processing using Python and OpenCV, all written and tested on Google Colab.

## 📚 Notebooks

| No. | Title | Description | Colab |
|-----|-------|-------------|-------|
| 01  | Contour Detection | Load an image, convert to grayscale, apply thresholding, and find contours using OpenCV. | [🔗 Open in Colab](https://colab.research.google.com/github/snz-mlcoder/image-processing-practice/blob/main/01-contour-detection.ipynb) |
| 02  | Contour Features | Bounding boxes, min area rectangles, and enclosing circles | [🔗 Open in Colab](https://colab.research.google.com/github/snz-mlcoder/image-processing-practice/blob/main/02-contour-bounding-box.ipynb) |
| 03  | Contour Cleanup | Basic vs improved contour detection with morphological operations | [🔗 Open in Colab](https://colab.research.google.com/github/snz-mlcoder/image-processing-practice/blob/main/03-contour-cleanup.ipynb) |
| 04  | Contour Approximation & Hull | Uses approxPolyDP and convex hull for contour analysis | [🔗 Open in Colab](https://colab.research.google.com/github/snz-mlcoder/image-processing-practice/blob/main/04-contour-approximation-and-hull.ipynb) |
| 05  | Line Detection – Hough Transform | Line detection using Canny edge and probabilistic Hough transform | [🔗 Open in Colab](https://colab.research.google.com/github/snz-mlcoder/image-processing-practice/blob/main/05-hough-lines-detection.ipynb) |
| 06  | Circle Detection – Hough Transform | Detects circular objects (coins) using HoughCircles with param tuning | [🔗 Open in Colab](https://colab.research.google.com/github/snz-mlcoder/image-processing-practice/blob/main/06-hough-circle-detection.ipynb) |
| 07  | Stereo Vision – Disparity Map | Computes disparity map from stereo image pair using StereoSGBM | [🔗 Open in Colab](https://colab.research.google.com/github/snz-mlcoder/image-processing-practice/blob/main/07-stereo-disparity-map.ipynb) |
| 08  | Depth Map – Class-Based | Object-oriented stereo depth map computation with SGBM and Matplotlib | [🔗 Open in Colab](https://colab.research.google.com/github/snz-mlcoder/image-processing-practice/blob/main/08-depthmap-class-based.ipynb) |
| 09  | GrabCut Segmentation | Foreground extraction using GrabCut algorithm with rectangular initialization | [🔗 Open in Colab](https://colab.research.google.com/github/snz-mlcoder/image-processing-practice/blob/main/09-grabcut-segmentation.ipynb) |
| 10  | Watershed Segmentation | Image segmentation using Watershed with Otsu thresholding and distance transform | [🔗 Open in Colab](https://colab.research.google.com/github/snz-mlcoder/image-processing-practice/blob/main/10-watershed-segmentation.ipynb) |
| 11  | Harris Corner Detection | Detects corner features in an image using OpenCV’s Harris corner algorithm | [🔗 Open in Colab](https://colab.research.google.com/github/snz-mlcoder/image-processing-practice/blob/main/11-harris-corner-detection.ipynb) |
| 12  | SIFT with Keypoint Filtering | Detects and visualizes strong keypoints using OpenCV SIFT with a response-based filter | [🔗 Open in Colab](https://colab.research.google.com/github/snz-mlcoder/image-processing-practice/blob/main/12-sift-keypoints-filtered.ipynb) |
| 13  | ORB Feature Matching | Detects and matches keypoints between two images using ORB and Brute-Force with Hamming distance | [🔗 Open in Colab](https://colab.research.google.com/github/snz-mlcoder/image-processing-practice/blob/main/13-orb-feature-matching.ipynb) |
| 14  | ORB + KNN + Ratio Test | Uses ORB and knnMatch with Lowe's ratio test to improve matching accuracy | [🔗 Open in Colab](https://colab.research.google.com/github/snz-mlcoder/image-processing-practice/blob/main/14-orb-knn-ratio-test.ipynb) |
| 15  | SIFT + FLANN Matching | Uses SIFT features with FLANN-based matcher and Lowe’s ratio test for robust feature matching | [🔗 Open in Colab](https://colab.research.google.com/github/snz-mlcoder/image-processing-practice/blob/main/15-sift-flann-feature-matching.ipynb) |
| 16  | SIFT + FLANN + Homography | Detects and matches keypoints with SIFT and FLANN, then estimates homography using RANSAC | [🔗 Open in Colab](https://colab.research.google.com/github/snz-mlcoder/image-processing-practice/blob/main/16-sift-flann-homography.ipynb) |
| 17  | SIFT + Homography Warping | Applies homography to warp the query image and overlay it onto the scene | [🔗 Open in Colab](https://colab.research.google.com/github/snz-mlcoder/image-processing-practice/blob/main/17-sift-warp-homography.ipynb) |
| 18  | People Detection – HOG | Detects pedestrians using HOG features with SVM classifier and filters nested rectangles | [🔗 Open in Colab](https://colab.research.google.com/github/snz-mlcoder/image-processing-practice/blob/main/18-PeopleDetection-HOG.ipynb) |


---

## 🚀 How to Use

1. Clone this repo:
   ```bash
   git clone https://github.com/snz-mlcoder/image-processing-practice.git
