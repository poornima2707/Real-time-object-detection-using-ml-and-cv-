# Real-time-object-detection-using-ml-and-cv-
**Overview**


This project uses YOLOv8 for real-time object detection in images and video streams. It is designed for crowd monitoring, surveillance, and pedestrian detection, with a focus on detecting people accurately.

**Dataset**


The People Detection Dataset from Roboflow contains 7,261 images with YOLO, COCO, and Pascal VOC annotations. It is split into:


1) Training: 80% (~5,800 images)


2) Validation: 10% (~725 images)


3) Testing: 10% (~725 images)

**Challenges & Solutions**


Small dataset: Used data augmentation (flipping, brightness changes).
Slow training: Optimized with YOLO Nano and planned GPU training.
Low accuracy for small objects: Increased input size to 640x640.
Real-time lag: Tuned inference parameters for smoother performance.

**Future Improvements**


Expand dataset for better generalization.
Optimize for higher FPS in real-time detection.
Deploy on cloud (AWS) or edge devices (Raspberry Pi).
Develop a GUI/API for easier usability.

**Results**


![Screenshot 2025-04-03 112848](https://github.com/user-attachments/assets/27ab530d-647e-4d97-81a9-e4007a1bd740)
![Screenshot 2025-04-03 112730](https://github.com/user-attachments/assets/7cb0247f-2b52-4b79-a26d-9a5f1bd9234e)
![Screenshot 2025-04-03 113044](https://github.com/user-attachments/assets/815029fd-8135-4bf9-941b-c80aeed59c50)
![Screenshot 2025-04-03 112652](https://github.com/user-attachments/assets/136afaa6-355b-4633-8506-91ff6a1329df)
![Screenshot 2025-04-03 113125](https://github.com/user-attachments/assets/fbbba774-c687-4813-be08-76319b563eb4)







