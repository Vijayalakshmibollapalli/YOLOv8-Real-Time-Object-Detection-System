# 🚀 YOLOv8 Real-Time Object Detection & Tracking System

An AI-powered Real-Time Object Detection and Tracking System developed using **YOLOv8**, **OpenCV**, and **Python**.
This project uses Deep Learning and Computer Vision techniques to detect, track, and count multiple objects in real time through a webcam feed.

### Project Overview

This system captures live video from a webcam and performs real-time object detection using the YOLOv8 model from Ultralytics. 

The application can 
* Detect multiple objects simultaneously
* Track objects across frames
* Count objects dynamically
* Display real-time FPS performance
* Capture screenshots
* Record processed video output

### Features

* Real-Time Object Detection
* Multi-Object Detection & Tracking
* Live Webcam Processing
* Object Counting System
* FPS (Frames Per Second) Monitoring
* Screenshot Capture Feature
* Video Recording Functionality
* Bounding Boxes with Labels & IDs
* Lightweight & Fast YOLOv8 Inference

### Technologies Used

| Technology  | Purpose                |
| ----------- | ---------------------- |
| Python      | Programming Language   |
| YOLOv8      | Object Detection Model |
| OpenCV      | Video Processing & UI       |
| Ultralytics | YOLO Framework         |
| NumPy       | Numerical Operations   |
| Pillow      | Image Handling         |

### Output Preview

![Image](https://images.openai.com/static-rsc-4/H9rrhkHZG94tVutPXnng_iWTu7-2O4i68P3m75jxVeX-XhB4ocCLHla4OCvWrwo0Wuu4leqVoZk5oTIj0dt3DIkswGLXBreOhxhAdgbc1qFQBcl2fUZbtzPWkRznvK3e8fkZD_ZtHi5y6xXTIobJSesGSaNyLOsfR-nQaVOG4vS3-KXRRMstS7EsUjF4AvBH?purpose=fullsize)

### Keyboard Controls

| Key   | Action                     |
| ----- | -------------------------- |
| **Q** | Quit Application           |
| **S** | Save Screenshot            |
| **R** | Start/Stop Video Recording |

### How the System Works

1. OpenCV captures live webcam frames
2. YOLOv8 processes each frame for object detection
3. Objects are tracked using persistent IDs
4. Bounding boxes and labels are drawn
5. Object counts are calculated dynamically
6. FPS is displayed for performance monitoring
7. Frames are optionally saved as images or video

### Object Detection Example

```bash
person: 3
car: 2
bottle: 1
FPS: 30
```

### Screenshot Feature

Press:

```bash
S
```

The screenshot will automatically save as:

```bash
screenshot_<timestamp>.jpg
```

### Future Enhancements

* Face Recognition System
* Vehicle Number Plate Detection
* AI Smart Surveillance System
* Custom YOLO Model Training
* Motion Detection Alerts
* Video Recording System
* Crowd Monitoring Application

### Requirements.txt

```txt
ultralytics
opencv-python
numpy
pillow
```
