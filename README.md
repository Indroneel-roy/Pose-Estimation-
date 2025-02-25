# Real-Time Pose Estimation and Fitness Tracking

This project performs **real-time pose estimation** and **fitness tracking** using OpenCV and MediaPipe Pose. It tracks body movements and counts repetitions for fitness activities.

## Features
- Real-time **pose detection** using MediaPipe
- **Fitness tracking** with rep counting
- Works with a webcam for live analysis

## Installation
Ensure you have Python installed, then install the required dependencies:

```bash
pip install opencv-python mediapipe numpy
```

## Usage
Since this project is implemented in a Jupyter Notebook, run the following command to start Jupyter Notebook:

```bash
jupyter notebook
```

Then, open **pose_estimation.ipynb** and run the cells to execute the pose estimation.

## Dependencies
The project requires the following libraries:
```python
import cv2
import mediapipe as mp
import numpy as np
mp_drawing = mp.solutions.drawing_utils
mp_pose = mp.solutions.pose
```

## Acknowledgments
This project is inspired by [nicknochnack's MediaPipe Pose Estimation](https://github.com/nicknochnack/MediaPipePoseEstimation/blob/main/Media%20Pipe%20Pose%20Tutorial.ipynb).





