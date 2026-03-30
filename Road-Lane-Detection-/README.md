# 🚗 Real-Time Road Lane Detection

A computer vision pipeline built with **Python** and **OpenCV** to identify and track road lane boundaries in video streams. This project serves as a foundational step for **Advanced Driver Assistance Systems (ADAS)** and autonomous vehicle navigation.

---

## 🌟 Key Highlights
* **Real-time Processing**: Optimized for high-speed frame analysis using NumPy.
* **Robust Detection**: Efficiently handles straight and dashed lane lines.
* **Mathematical Precision**: Uses Canny Edge Detection and Hough Transforms for accurate boundary mapping.

## 🛠️ Technical Pipeline
The system processes each video frame through a multi-stage pipeline:
1. **Grayscale Conversion**: Simplifies the image for faster processing.
2. **Gaussian Blur**: Reduces image noise to prevent false edge detection.
3. **Canny Edge Detection**: Identifies sharp changes in pixel intensity to find lane markings.
4. **Region of Interest (ROI)**: Masks the image to focus exclusively on the road area.
5. **Hough Line Transform**: Converts detected edge pixels into geometric line segments.
6. **Extrapolation**: Averages the detected lines to create a smooth, solid overlay on the original video.

## 🚀 Getting Started

### Prerequisites
Ensure you have the following installed on your MacBook:
* Python 3.x
* OpenCV (`pip install opencv-python`)
* NumPy (`pip install numpy`)

### Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/


