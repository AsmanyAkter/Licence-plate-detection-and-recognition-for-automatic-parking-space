# License Plate Detection and Recognition for Automatic Parking Space
This project implements a system for detecting and recognizing license plates in automatic parking spaces. The solution is built using YOLO-based object detection models for license plate localization and PaddleOCR for text recognition.

# Project Overview
The project aims to create a robust and efficient license plate detection and recognition system. The pipeline involves:
1. Detecting license plates in images using YOLO models.
2. Extracting text from detected plates using Optical Character Recognition (OCR) with PaddleOCR.

# Dataset
The dataset consists of:
Original Images: 652 images collected from diverse sources.
Augmented Data: 20% of images were augmented with rain, fog, and shadow conditions.

Splits:
Training: 70%
Validation: 20%
Testing: 10%

# Models Used
YOLOv8n (Nano): Achieved the best performance in detection tasks.

YOLOv8s (Small): A lightweight model used for comparison.

YOLOv9c: Tested for performance benchmarking.

Best Detection Model: YOLOv8n was selected based on evaluation metrics (Box P, R, mAP50, and mAP50-95).

Text Recognition: PaddleOCR was integrated for extracting the text from detected license plates.

