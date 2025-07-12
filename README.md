#  YOLOSagnik: Real-Time Phone & Person Detection

YOLOSagnik is a **real-time detection system** that uses YOLOv8, Haar Cascades, and MediaPipe to detect cell phones, people, and faces from your webcam feed. Designed for proctoring and security applications, it overlays live detection results and statistics.


##  Features

-  Detects mobile phones using **YOLOv8**.
-  Detects people and faces using **Haar Cascades** & **MediaPipe**.
-  Live detection count overlays on the video feed.
-  Runs directly on webcam input for real-time performance.
-  Compatible with OpenCV without Streamlit or matplotlib dependencies.

##  Requirements

| Package          | Version           |
|------------------|-------------------|
| Python           | >=3.8             |
| OpenCV           | >=4.5             |
| Ultralytics      | >=8.0             |
| MediaPipe        | >=0.10            |

Install all dependencies:
```bash
pip install opencv-python ultralytics mediapipe
