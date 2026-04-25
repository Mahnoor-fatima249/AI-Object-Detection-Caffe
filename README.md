# Object Detection using MobileNet-SSD & OpenCV

This is my 4th AI project during my internship at **DecodeLab**. In this project, I implemented real-time object detection using a pre-trained **Caffe Model**.

## 🚀 How it Works
The project uses the **MobileNet-SSD** architecture which is efficient for detecting multiple objects in an image. It can recognize 21 different classes including persons, cars, chairs, bottles, and more.

## 📁 Project Structure
- `main.py`: The core Python logic using OpenCV's DNN module.
- `MobileNetSSD_deploy.prototxt`: Defines the model architecture.
- `MobileNetSSD_deploy.caffemodel`: Contains the pre-trained weights (Knowledge) for detection.
- `test.jpg`: Input image for testing the AI.

## 🛠️ Requirements
- Python 3.x
- OpenCV (`cv2`)
- NumPy

## 📊 Results
The model successfully identifies objects with a confidence score (e.g., Person: 92%).
