Object Segmentation with SAM Model


This project demonstrates object segmentation using the SAM (Segment Anything Model) from Ultralytics. The goal is to load a pre-trained SAM model and perform segmentation on input images or videos, extracting and displaying individual objects via their bounding boxes.

Features:
Object Detection: Uses SAM to detect and segment objects in images/videos.
Bounding Box Extraction: Crops the segmented objects based on bounding box coordinates.
Cropped Image Display: Displays each segmented object in a separate window.
Cropped Image Saving: Optionally saves each segmented object as an individual image file.

Requirements:
Python 3.x
torch
opencv-python
ultralytics
matplotlib

Example Output:
Segmented objects are displayed with their bounding boxes.

Each object can be saved as a separate image file.

The link for the output video file is given here: https://drive.google.com/file/d/1DpHqaMpn4hGm-Q27QNyyUyTmpCZi9MX2/view?usp=sharing
