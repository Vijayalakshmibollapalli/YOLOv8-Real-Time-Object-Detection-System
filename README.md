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

## 📷 Project Output

![Image](https://images.openai.com/static-rsc-4/Ch9Kn-kU-A5rihuwWV6b-HV0O9l_5gryKVX7tXSQrSmonJnbevZrxC_AGkrVQRqBT8fdY4nhjxcfexHmQ1TAX7Hihex4OKY5BKwKx9Z0jfFFJMl15kqlOv1ol2Ri8ebhfp3pJiKVAA-AeXC5i7gRVj8RbKil73dcP39_qsJ9mjl5jVns3iP9yd93JTdEAiPM?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/HatZGP4KH2ftEPhRMLFgX9TP5QeNzQVrNZZIxlfolq3-ri7B68F5PMzgfhXeDlXh9cfrypEC_bgLlawwb88RSLtl8PnUQv4J2qquJ5Fz7KzFOdiINlaOnAlNXh17RAN3wszMPMf846BN5p0e3klPk3-AtXnHbgKOABCFMo1o4ynr1dt_WTuyFCFudZ01qiuY?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/IwJuKDvlPblANgTVq52C_BbTs6xlz9W9YGK9SZ_B6rT7sHO07Ix0DWIGivmbV_8MwWR1NubX9nOUCPpaaEXd9PZqvNfx9cndfqNYAF2ZyJtLhM6P5dKnqGzSHruD9uHng8QZ-fr-nDxb8qbhtmDc9G7hLbzSuM8f9C5csWXRN-34m-3Wc6w3Nxgx-_FdZokP?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/j8UeO6StsyFpYRULid6Uqr7Y9fDy_wEkWwXHsrshzbK_AH6aMguzLsHBe0nGRCzj6DMf-ZZnj2drX4L0REKzOIXMShTxrYAaFtTidE_u5Lytwyg639Peq6mYRTQnu-ha0IwpYhsj8rAQkMg_5Kl6tV4qEoZ8SnAiXmsGqHG5wus90t6M-q95W5SaEdOr3SZx?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/qaRy14RC_csj6Z6ISgcdPCs7f8CuyGehdIXdckG2FzQMKdHlVRWIs0BwsvlCrnFkSoSYPfKCyprJrAlxD26PPluMqqmqz1AYql7Ldg0LmGJv0_cR_PXZe3OVhrzbRIRR8b5-mM8M50utOD14nrc1gJ9ao55Kjjg2basUeZiSKrWKIWNXRcY3nvkoLLxlVWXZ?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/Dv9M7elmMzZcgLQ1VoOITTzD1tf8RSynWWxMVPNV0NjrgbP2Otct95exkxMTPF0Y-FyrmPvrYtzHHLvCH_qL171Q9f4CCj-5FRuVAsAR6enDdpW4vtLpZQlvTk2v90x9tUalL8BkMPPAZGh_rQkhL0inQvVb3PEeOrczVgZzILEEhzb319PRmYvF077uEf6L?purpose=fullsize)

# Controls

| Key | Function         |
| --- | ---------------- |
| Q   | Quit application |
| S   | Save screenshot  |

# How It Works

1. Webcam captures live video frames.
2. YOLOv8 model processes each frame.
3. Objects are detected and tracked.
4. Bounding boxes are drawn around objects.
5. FPS and object counts are displayed live.

# YOLOv8 Model

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

---

# Screenshot Feature

Press:

```bash
S
```

Screenshots will automatically save as:

```bash
screenshot_timestamp.jpg
```

---

# Example Output

```bash
person: 3
car: 2
bottle: 1
FPS: 28
```

# Future Improvements
* Face recognition integration
* Vehicle number plate detection
* Custom dataset training
* GUI dashboard
* Email alert system
* Crowd monitoring system
* AI surveillance system

# Requirements.txt

```txt
ultralytics
opencv-python
pillow
numpy
```
