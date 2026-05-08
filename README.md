# 🚀 YOLOv8 Real-Time Object Detection & Tracking System

An AI-powered Real-Time Object Detection and Tracking System developed using **YOLOv8**, **OpenCV**, and **Python**.
This project uses Deep Learning and Computer Vision techniques to detect, track, and count multiple objects in real time through a webcam feed.

### Project Overview

This system captures live video from a webcam and performs real-time object detection using the YOLOv8 model from Ultralytics. The application can identify multiple objects simultaneously, draw bounding boxes around them, track detected objects, display FPS performance, and count the number of detected objects.

### Features

* Real-Time Object Detection
* Multi-Object Detection & Tracking
* Live Webcam Processing
* Object Counting System
* FPS (Frames Per Second) Monitoring
* Screenshot Capture Feature
* Bounding Boxes with Labels
* High-Speed YOLOv8 Inference

### Technologies Used

| Technology  | Purpose                |
| ----------- | ---------------------- |
| Python      | Programming Language   |
| YOLOv8      | Object Detection Model |
| OpenCV      | Video Processing       |
| Ultralytics | YOLO Framework         |
| NumPy       | Numerical Operations   |
| Pillow      | Image Handling         |

### Output Preview

![Image](https://images.openai.com/static-rsc-4/H9rrhkHZG94tVutPXnng_iWTu7-2O4i68P3m75jxVeX-XhB4ocCLHla4OCvWrwo0Wuu4leqVoZk5oTIj0dt3DIkswGLXBreOhxhAdgbc1qFQBcl2fUZbtzPWkRznvK3e8fkZD_ZtHi5y6xXTIobJSesGSaNyLOsfR-nQaVOG4vS3-KXRRMstS7EsUjF4AvBH?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/IwJuKDvlPblANgTVq52C_BbTs6xlz9W9YGK9SZ_B6rT7sHO07Ix0DWIGivmbV_8MwWR1NubX9nOUCPpaaEXd9PZqvNfx9cndfqNYAF2ZyJtLhM6P5dKnqGzSHruD9uHng8QZ-fr-nDxb8qbhtmDc9G7hLbzSuM8f9C5csWXRN-34m-3Wc6w3Nxgx-_FdZokP?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/Dv9M7elmMzZcgLQ1VoOITTzD1tf8RSynWWxMVPNV0NjrgbP2Otct95exkxMTPF0Y-FyrmPvrYtzHHLvCH_qL171Q9f4CCj-5FRuVAsAR6enDdpW4vtLpZQlvTk2v90x9tUalL8BkMPPAZGh_rQkhL0inQvVb3PEeOrczVgZzILEEhzb319PRmYvF077uEf6L?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/CSaKK37WKUKOT2k3JdtPTo44002Ke8qqZNrnqCZ53t-52_q7rpRZHnynlUgmcehSEMS2asBG5c7EB9uCLgWiU8Pai6_uARoEtIG93X6WO10rWG2yniQnBVDPKs743woLk23Tfs8mlY-9cawGE_frUZkDMEGSwrhKh7IrLViv8N2rRTm4X3fISWvXMmwMFXzX?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/j8UeO6StsyFpYRULid6Uqr7Y9fDy_wEkWwXHsrshzbK_AH6aMguzLsHBe0nGRCzj6DMf-ZZnj2drX4L0REKzOIXMShTxrYAaFtTidE_u5Lytwyg639Peq6mYRTQnu-ha0IwpYhsj8rAQkMg_5Kl6tV4qEoZ8SnAiXmsGqHG5wus90t6M-q95W5SaEdOr3SZx?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/VVZyZb-AxHux-1vP-LNIhvPLZ-p2y3e9z_nncyQmgbLmFFGld1NYAfi_-WYHgwyoEFtdiSgckL_lj2FqT1FcgOvTexmV3bKYbOzfgNfU4kxN1-l19_LjPmEh70b97FvpLTbLGs2PRTazlKX5FY-wa_gbqHVIs39u_Dgtd4z9b0TKPSuZrQJIDiuJ5cNmAnXW?purpose=fullsize)

### Keyboard Controls

| Key | Action           |
| --- | ---------------- |
| Q   | Quit Application |
| S   | Save Screenshot  |

### How the System Works

1. OpenCV captures live webcam frames.
2. YOLOv8 processes each frame for object detection.
3. Detected objects are tracked in real time.
4. Bounding boxes and labels are displayed.
5. FPS and object counts are updated continuously.

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
screenshot_timestamp.jpg
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
