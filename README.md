# IndianNumberPlateDetectionUsingYolov8
This repository contains a deep learning project for detecting Indian vehicle number plates using YOLOv8 and performing OCR (Optical Character Recognition) to extract text from detected plates. The project is designed to work on images and videos for real-time applications.

Features

Detect Indian number plates from images and video streams.

OCR recognition using EasyOCR to extract number plate text.

Right-to-left reading order for multi-row plates.

Zoomed-in bounding box for better OCR accuracy.

Display recognized text directly on images/videos.

Dataset

Custom dataset of Indian number plates collected from public sources and manually annotated using Roboflow.

Dataset includes multiple plate formats (single-row and double-row plates).

Annotated in YOLO format (.txt with [class, x_center, y_center, width, height]).

Requirements

Python 3.8+

Ultralytics YOLO
 (pip install ultralytics)

EasyOCR (pip install easyocr)

OpenCV (pip install opencv-python)

yolov8-indian-number-plate-detection/
│
├── dataset/                # Images and annotations
├── detect.py               # Image detection script
├── detect.py         # detection script
├── best.pt                 # Trained YOLOv8 model
├── README.md               # Project documentation
└── requirements.txt        # Python dependencies


References

YOLOv8 Documentation

EasyOCR GitHub

Roboflow for Dataset Annotation
