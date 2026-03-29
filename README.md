# "Object Detection, Classification, and Recognition in Autonomous Cars using SSD Model"
Focuses on developing a system that enables autonomous vehicles to detect, classify, and recognize objects in real-time. By leveraging the SSD (Single Shot Multibox Detector) model, your project aims to improve the vehicle's ability to identify various objects in its environment, such as pedestrians, other cars, traffic signs, and road obstacles.

The Object Detection part of project involves locating these objects in images or video streams captured by the car's sensors. Classification assigns labels to these objects, like "car" or "pedestrian," while Recognition helps the system understand specific attributes, like recognizing the color of traffic lights. Your project aims to enhance the accuracy and speed of these processes, ensuring the car can make safe, real-time decisions while navigating roads.

## Features
- Real-time object detection using SSD model  
- Detects objects like cars, pedestrians, traffic lights  
- Supports both webcam and video input  
- Displays bounding boxes with labels and confidence scores  

## Tech Stack
- Python  
- PyTorch  
- OpenCV  
- Torchvision  

## Model Used
- SSD Lite (ssdlite320_mobilenet_v3_large)  
- Pre-trained on COCO dataset  

## Dataset
- COCO dataset (pre-trained weights used)  

## How to Run

### 1. Install dependencies
pip install torch torchvision opencv-python  

### 2. Run the project
python main.py  

## Input
- Webcam (real-time)  
- Video file  

## Output
- Detected objects with:
  - Bounding boxes  
  - Labels  
  - Confidence score  
