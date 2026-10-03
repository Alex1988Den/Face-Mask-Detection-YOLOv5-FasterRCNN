# 😷 Face Mask Detection Using YOLOv5 and Faster R-CNN
 
## 📌 Project Overview
 
This project focuses on face mask detection using modern deep learning object detection architectures.
 
The project compares one-stage and two-stage object detectors, specifically YOLOv5 and Faster R-CNN, to identify and localize faces wearing masks in images.
 
The primary goal was to develop a reliable object detection system capable of accurately detecting face masks and evaluating performance using industry-standard computer vision metrics.
 
---
 
## 🎯 Project Objectives
 
- Train object detection models for face mask detection
- Compare YOLOv5 and Faster R-CNN architectures
- Detect and localize faces using bounding boxes
- Evaluate detection quality using IoU and Average Precision
- Achieve validation performance above 85%
 
---
 
## 📊 Dataset
 
The dataset contains facial images belonging to three categories:
 
- Face With Mask
- Face Without Mask
- Incorrectly Worn Mask
 
Bounding box annotations were used for object detection training and evaluation.
 
---
 
## 🧠 Deep Learning Models
 
### YOLOv5
 
A single-stage object detector optimized for fast and efficient real-time detection.
 
### Faster R-CNN
 
A two-stage object detector designed to achieve high localization and detection accuracy.
 
---
 
## 📏 Evaluation Metrics
 
Model performance was evaluated using:
 
### Intersection over Union (IoU)
 
Measures how accurately predicted bounding boxes overlap with ground truth annotations.
 
### Average Precision (AP)
 
Measures overall object detection quality across different confidence thresholds.
 
---
 
## 🔍 Project Workflow
 
### 1. Data Preparation
 
- Dataset loading
- Annotation processing
- Image preprocessing
 
### 2. Model Training
 
- YOLOv5 training
- Faster R-CNN training
- Hyperparameter tuning
 
### 3. Model Evaluation
 
- Validation set evaluation
- IoU measurement
- Average Precision calculation
 
### 4. Result Visualization
 
- Detection examples
- Bounding box visualization
- Performance comparison
 
---
 
## 📈 Results
 
### ✅ Validation Accuracy Above 85%
 
Key observations:
 
- Stable loss convergence during training
- Consistent improvement in detection quality
- Maximum Average Precision (AP) score of **0.8451**
- Reliable face mask localization and classification performance
 
---
 
## 🛠 Technologies
 
- Python
- PyTorch
- YOLOv5
- Faster R-CNN
- OpenCV
- NumPy
- Matplotlib
- Jupyter Notebook
 
---
 
## 🚀 Installation
 
Clone the repository:
 
```bash
git clone https://github.com/Alex1988Den/Face-Mask-Detection-YOLOv5-FasterRCNN.git
cd Face-Mask-Detection-YOLOv5-FasterRCNN
```
 
Install dependencies:
 
```bash
pip install -r requirements.txt
```
 
Launch Jupyter Notebook:
 
```bash
jupyter notebook
```
 
Open:
 
```text
Face_Mask_Detection_YOLOv5_FasterRCNN.ipynb
```
 
and run all cells.
 
---
 
## 💡 Applications
 
- Public Safety Monitoring
- Smart Surveillance Systems
- Workplace Safety Compliance
- Real-Time Face Mask Detection
- Computer Vision Research
 
---
 
## 👨‍💻 Author
 
Developed by **Aleksandr Denissov**
 
📧 Email: aleksandr.denissov@brave.ee
 
---
 
⭐ If you find this project useful, feel free to leave a star on GitHub.
