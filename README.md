# Touchless-media-control

# Gesture Based Volume & Media Control 

A touchless human computer interaction system enabling gesture based volume and media control using computer vision.

This project focuses on real-world constraints, not just gesture detection accuracy.

# Overview

Traditional media control depends on physical input devices such as keyboards, mice, or remotes.  
This project explores a "touchless alternative" using computer vision and AI-based hand keypoint detection.

# Features

-  Dynamic Volume Slider:
  - Thumb–index distance controls volume smoothly                                                                              
  - Prevents false triggers

- Touchless Play / Pause:
  - Hand-raise gesture above a 40% of the frame.

- System Level Integration:
  - Direct control of Windows media keys
  - No additional hardware required

# Tech Stack

- Python
- YOLO (Ultralytics) — Hand Keypoint Detection
- OpenCV — Webcam & visualization
- NumPy — Numerical processing
- Windows Media Keys — OS-level control

# How It Works

1. Capture webcam frames using OpenCV
2. Detect 21 hand keypoints using YOLO(a trained model)
3. Interpret gestures
4. Trigger media actions

# Demo

Demo Video:  
Test:https://youtu.be/x_AGR9c5ZhM
Working:https://youtu.be/dXByQ8O1E9A

# Limitations

- Performance depends on lighting and camera quality
- Gesture accuracy decreases at long distances (depends on quality and quantity of the trained dataset)
- Currently optimized for Windows systems

# Author

Built and designed by Darshan. 
Focus: AI, Computer Vision, and Human Computer Interaction
