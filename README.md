# AI-Based Real-Time Surveillance System (Edge AI)

## Overview
This project implements a real-time AI-powered surveillance system using YOLO-based deep learning models deployed on an NVIDIA Jetson Nano for edge inference. The system performs live object detection, segmentation, fire detection, motion detection, and intruder alerting using CCTV video streams with low latency.

This project was developed and deployed during my Embedded Systems & AIoT internship, focusing on production-like edge AI performance rather than academic demos.

---

## Problem Statement
Traditional CCTV surveillance systems rely heavily on manual monitoring, which leads to delayed responses and human error. The goal of this project is to automate surveillance tasks by running real-time computer vision models directly on an edge device, enabling faster alerts and reduced cloud dependency.

---

## System Architecture
**Input:** Live CCTV video feed  
**Processing:** YOLO-based real-time inference on Jetson Nano  
**Output:** Visual overlays and alert triggers (intrusion, fire, motion, segmentation)


---

## Technology Stack
- **Hardware:** NVIDIA Jetson Nano
- **Languages:** Python
- **Computer Vision:** YOLO, OpenCV
- **OS:** Linux (JetPack SDK)

---

## Key Features
- Real-time object detection and segmentation
- Fire detection and intruder alerting
- Motion detection using live video streams
- Edge-based inference without cloud dependency
- Optimized inference pipeline for embedded deployment

---

## Performance & Optimization
- Deployed on Jetson Nano with live CCTV input
- Optimized processing pipeline resulting in **~35% improvement in inference efficiency**
- Designed for low-latency edge alerts


---

## Demo Results
![Detection Output](assets/)


---

## Challenges Faced
- Achieving real-time performance on resource-constrained hardware
- Handling latency in live video streams
- Optimizing model inference for edge deployment

---

## Future Improvements
- TensorRT optimization
- Quantized model deployment
- Training with a custom dataset
- Multi-camera scalability

---

## Impact
This project demonstrates hands-on experience in deploying real-time computer vision systems on edge devices, combining embedded systems, AI, and hardware–software integration in a production-oriented setup.
