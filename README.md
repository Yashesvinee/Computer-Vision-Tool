# Vision-Based Posture Assessment Tool

**A computer vision framework for real-time ergonomic posture analysis and correction.**

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![OpenCV](https://img.shields.io/badge/OpenCV-Computer%20Vision-green)
![Status](https://img.shields.io/badge/Status-Research%20Prototype-orange)

## 📌 Overview
This repository contains the source code and experimental data for my research on **vision-based posture assessment**, published in 2023. The tool utilizes computer vision techniques to detect human body keypoints in real-time, analyze ergonomic risks, and provide corrective feedback.

The system is designed to be **non-invasive** and **computationally efficient**, making it suitable for deployment on standard hardware without requiring specialized motion capture suits.

## 🚀 Key Features
* **Real-Time Pose Estimation:** Utilizes pose estimation libraries to extract skeletal keypoints from video feeds.
* **Ergonomic Risk Analysis:** Calculates joint angles (neck, back, shoulders) to identify poor posture based on RULA/REBA standards.
* **Data Visualization:** Generates visual overlays on the input video to highlight areas of concern (e.g., red lines for severe slouching).
* **Cross-Platform Support:** Built with Python for easy deployment on Windows, Linux, and macOS.

## 🛠️ Tech Stack
* **Language:** Python
* **Computer Vision:** OpenCV, MediaPipe (or YOLO/OpenPose - update this based on your code)
* **Data Processing:** NumPy, Pandas
* **Visualization:** Matplotlib

## ⚙️ Installation

1.  **Clone the repository**
    ```bash
    git clone [https://github.com/Yashesvinee/Computer-Vision-Tool.git](https://github.com/Yashesvinee/Computer-Vision-Tool.git)
    cd Computer-Vision-Tool
    ```

2.  **Install dependencies**
    ```bash
    pip install -r requirements.txt
    ```

## 💻 Usage

To run the posture detection on a webcam feed:

```bash
python main.py --source 0
