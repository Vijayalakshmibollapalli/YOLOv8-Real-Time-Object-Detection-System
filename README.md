# 🚀 YOLOv8 Real-Time Object Detection System

A powerful real-time Object Detection and Tracking System built using **YOLOv8**, **OpenCV**, and **Python**.
This project detects multiple objects from a webcam feed, tracks them live, displays FPS performance, and counts detected objects in real-time.

## Features
* Real-time object detection using YOLOv8
* Object tracking with persistent IDs
* Live webcam detection
* FPS (Frames Per Second) monitoring
* Real-time object counting
* Screenshot capture functionality
* Fullscreen/OpenCV window support
* Fast and lightweight implementation

## Technologies Used
* Python
* OpenCV
* YOLOv8
* Ultralytics
* NumPy
* Pillow

### Controls

| Key | Function         |
| --- | ---------------- |
| Q   | Quit application |
| S   | Save screenshot  |

### How It Works

1. Webcam captures live video frames.
2. YOLOv8 model processes each frame.
3. Objects are detected and tracked.
4. Bounding boxes are drawn around objects.
5. FPS and object counts are displayed live.

### YOLOv8 Model

This project uses:

```python
YOLO("yolov8s.pt")
```

You can also use:

| Model      | Speed   | Accuracy |
| ---------- | ------- | -------- |
| yolov8n.pt | Fastest | Lower    |
| yolov8s.pt | Fast    | Good     |
| yolov8m.pt | Medium  | Better   |
| yolov8l.pt | Slower  | High     |
| yolov8x.pt | Slowest | Best     |

### Screenshot Feature

Press:

```bash
S
```

Screenshots will automatically save as:

```bash
screenshot_timestamp.jpg
```

### Example Output

```bash
person: 3
car: 2
bottle: 1
FPS: 28
```

### Future Improvements
* Face recognition integration
* Vehicle number plate detection
* Custom dataset training
* GUI dashboard
* Email alert system
* Crowd monitoring system
* AI surveillance system

### Requirements.txt

```txt
ultralytics
opencv-python
pillow
numpy
```
