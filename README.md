📘 Computer Vision Lab 09

Real-Time Object Detection using YOLOv8

📌 Overview

This notebook demonstrates the implementation of real-time object detection using the YOLOv8 model. It applies object detection techniques to multiple real-world scenarios such as surveillance, retail, education, and industry.

⚙️ Technologies Used
Python
OpenCV (cv2)
Ultralytics YOLOv8
Matplotlib
MoviePy
🚀 Features
Real-time object detection on images and videos
Multiple case studies for practical applications
Visualization of detected objects with bounding boxes
Lightweight YOLOv8 (yolov8n.pt) model for fast performance
📂 Case Studies Implemented
1. Smart Traffic Surveillance
Detects vehicles and objects in traffic scenes
Helps in traffic monitoring and control
2. Public Park Surveillance
Identifies people and activities
Useful for safety and crowd monitoring
3. Retail Checkout Automation
Detects products for automated billing
Reduces manual checkout effort
4. Smart Classroom Monitoring
Tracks student presence and engagement
Useful for attendance and behavior analysis
5. Smart Parking System
Detects vehicles in parking areas
Helps identify available parking slots
6. Wildlife Monitoring
Detects animals in natural habitats
Useful for conservation efforts
7. Industrial Defect Detection
Identifies defects in products
Improves quality control in manufacturing
8. Retail Shelf Analytics
Monitors products on shelves
Helps in inventory management
📁 Input Requirements
Image or video file paths (currently hardcoded in the notebook)
YOLOv8 pretrained model file (yolov8n.pt)

⚠️ Note: Update file paths according to your system before running.

▶️ How to Run
Install required libraries:
pip install ultralytics opencv-python matplotlib moviepy
Download YOLOv8 model (if not auto-downloaded):
yolo detect predict model=yolov8n.pt
Run the notebook cell by cell.
📊 Output
Images/videos with detected objects
Bounding boxes with labels
Real-time detection (for video cases)
🎯 Conclusion

This lab demonstrates how object detection can be applied across various domains using YOLOv8. It highlights the versatility of computer vision in solving real-world problems efficiently.
