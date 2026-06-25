# 🎮 Computer Vision Detection System

A real-time **Computer Vision Combat Analysis System** built with **Python** and **OpenCV** that analyzes gameplay footage without modifying the game.

The project detects and tracks players and enemies, estimates body pose, predicts attacks, and generates real-time combat analytics directly from video.

> **Current Demo:** Elden Ring - Tree Sentinel Boss Fight

---

## Features

* Real-time player and boss detection
* Multi-object tracking
* Human pose estimation
* Attack prediction
* Velocity estimation
* Threat level analysis
* Confidence scoring
* Distance measurement between entities
* Live combat analytics overlay
* Works on raw gameplay footage (No game mods)

---

## Tech Stack

* Python
* OpenCV
* NumPy
* YOLO *(Upcoming)*
* MediaPipe / Pose Estimation
* Computer Vision

---

## Pipeline

```text
Gameplay Video
      │
      ▼
Frame Extraction
      │
      ▼
Object Detection
      │
      ▼
Object Tracking
      │
      ▼
Pose Estimation
      │
      ▼
Motion Analysis
      │
      ▼
Attack Prediction
      │
      ▼
Combat Analytics
      │
      ▼
Real-Time Overlay
```

---

## Current Capabilities

* Detect player and boss
* Track movement in real time
* Estimate body keypoints
* Calculate velocity
* Compute distance between entities
* Predict incoming attacks
* Generate confidence scores
* Display combat information as an overlay

---

## Roadmap

### Version 1 ✅

* Basic object tracking
* Pose estimation
* Velocity analysis
* Threat detection
* Overlay system

### Version 2 🚧

* YOLO-based object detection
* Improved pose estimation
* Better tracking stability
* Multiple enemy support
* Improved attack prediction

### Version 3

* Action recognition
* Combat pattern learning
* Fight statistics dashboard
* Performance analytics
* Custom model training

---

## Repository Structure

```text
Computer-Vision-Detection-System/
│
├── data/
├── models/
├── videos/
├── outputs/
├── src/
│   ├── detection.py
│   ├── tracking.py
│   ├── pose.py
│   ├── prediction.py
│   ├── visualization.py
│   └── main.py
│
├── requirements.txt
├── README.md
└── LICENSE
```

---

## Installation

```bash
git clone https://github.com/Akshat19G/Computer-Vision-Detection-System.git

cd Computer-Vision-Detection-System

pip install -r requirements.txt

python src/main.py
```

---

## Future Improvements

* Fine-tuned YOLO model
* DeepSORT / ByteTrack integration
* 3D pose estimation
* Transformer-based attack prediction
* Temporal action recognition
* Multi-game compatibility
* Performance optimization
* GPU acceleration

---

## Demo

Coming Soon

---

## Contributing

Contributions, ideas, and feature requests are always welcome.

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Open a Pull Request

---

## Author

**Akshat Srivastava**

GitHub: https://github.com/Akshat19G

---

## License

This project is licensed under the MIT License.

---

⭐ If you found this project interesting, consider giving it a star. It helps support the project and future updates.
