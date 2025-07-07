# Blue Object Shape Detection with OpenCV

This project uses Python and OpenCV to detect **blue-colored objects** from a webcam feed and **approximate their shape** in real time.

Shapes are classified approximately as:
- **Rectangle**: if the number of polygonal approximation vertices is between 6 and 10.
- **Circle**: if the shape has more than 10 vertices.

## 🧠 Features

- Real-time detection using webcam
- HSV color filtering for blue object segmentation
- Noise reduction with morphological operations
- Contour detection and shape approximation
- Shape labeling directly on the video feed

## 📸 Example Output

https://github.com/user-attachments/assets/20c1fb9d-cb78-4c35-a46c-d6d011ca09a9

## 🚀 Getting Started

### Prerequisites

- Python 3.x
- OpenCV
- NumPy
