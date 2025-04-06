# mediapipe-3d-object-detection-

# 🧠 MediaPipe 3D Object Detection using Objectron

This project demonstrates 3D object detection using the **MediaPipe Objectron** model in Python. The model detects real-world objects (like cups or mugs) in static images and visualizes their **3D bounding boxes** and **orientation axes**.

---

## 📌 Features

- Fetch image from a URL and decode it.
- Detect objects (like cups) using MediaPipe Objectron.
- Draw 2D landmarks and 3D orientation axes.
- Visualize the final annotated result using Matplotlib.

---

## 🔧 Tech Stack / Libraries

- `MediaPipe` – For Objectron model and 3D object detection
- `OpenCV (cv2)` – For image decoding and color space conversion
- `NumPy` – To handle image arrays efficiently
- `urllib` – To fetch images from the web
- `Matplotlib` – For displaying the output

---

## 📂 Project Structure

```bash
.
├── objectron_detection.py     # Main script for object detection
├── requirements.txt           # Python dependencies
├── README.md                  # Project documentation
└── images/
    └── sample_image.jpg       # (Optional) Local test image
