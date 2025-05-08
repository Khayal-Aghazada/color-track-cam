# 🎯 ColorTrackCam

**ColorTrackCam** is a real-time object tracker that follows a green-colored object using your webcam. It uses OpenCV and MediaPipe for video processing and draws a visual trail showing the motion path.

---

## 🚀 Features

- 🎥 Real-time webcam tracking
- 🟢 Tracks **green-colored objects**
- 🌀 Visual trail of the tracked object
- 📹 Optional video file input
- 🧹 Smooth tracking using blur, masks, and contours

---

## 🛠️ Tech Stack

- **Python 3**
- **OpenCV**
- **imutils** (for resizing and contour utilities)
- **NumPy**

---

## 🧩 How It Works

1. Captures webcam or video stream
2. Converts frame to HSV color space
3. Detects green objects using color thresholding
4. Finds contours and centers
5. Draws a circle on the object and a line trail showing its movement

---

## 📦 Installation

### 🔧 Dependencies

Install required packages:

```bash
pip install opencv-python imutils numpy
