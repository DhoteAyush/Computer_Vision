# Computer_Vision
Computer Vision Algorithms: Harris Corner Detection, RANSAC with Feature Matching, and Keypoint Detection with SURF. This repository demonstrates popular computer vision techniques to detect and match image features, handle transformations, and visualize keypoints.

# 🖼️ Computer Vision Algorithms - SIFT, RANSAC, and Harris Corner Detection

This repository contains Python implementations of foundational computer vision algorithms to detect and match features between images. These techniques are widely used in image stitching, object recognition, and 3D reconstruction.

📂 Contents

1. SIFT (Scale-Invariant Feature Transform)
   - Detects scale- and rotation-invariant keypoints.
   - Matches keypoints between two images.
   - Visualizes matching points.
   - Requires `opencv-contrib-python`.

2. RANSAC (Random Sample Consensus) for Feature Matching
   - Detects and matches keypoints using ORB detector.
   - Uses RANSAC to remove outliers and compute a homography.
   - Shows robust matching between two images with transformations.

3. Harris Corner Detection
   - Detects corners in a grayscale image.
   - Visualizes corners by marking them on the image.

🛠️ Requirements

- Python 3.x
- OpenCV (`opencv-contrib-python` for SIFT)
- NumPy
- Matplotlib

### Install dependencies:
```bash
pip install opencv-contrib-python numpy matplotlib
