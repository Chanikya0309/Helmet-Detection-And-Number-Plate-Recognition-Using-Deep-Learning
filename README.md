Project: Helmet Detection & Number Plate Recognition Using Deep Learning
==========================================================================

Objective:
----------
This project simulates an automated traffic monitoring system that detects non-helmet riders and extracts their vehicle number plate using deep learning.

Contents:
----------
dataset – Images & videos of riders with/without helmets, vehicles with number plates

helmet_detection_model and number_plate_recognition.ipynb – Helmet detection using YOLOv3 and Number plate detection using YOLOv2 + OCR

README.txt – Project overview & execution guide

Instructions:
------------
Collect and prepare dataset (helmet/non-helmet images + vehicles).

Run helmet_detection_model and number_plate_recognition.ipynb to:

Detect motorcyclist & bike (YOLOv2)

Classify helmet vs. no helmet (YOLOv3)

Detect license plates (YOLOv2)

Extract plate numbers using OCR (Tesseract/EasyOCR).

Integrate models for real-time video input (CCTV or dashcam footage).

Key Features:
-------------
✔ Automatic helmet detection

✔ Number plate extraction & OCR recognition

✔ Real-time video frame analysis

✔ Alert generation for violations

✔ Scalable for smart traffic & law enforcement systems

Tools Recommended:
-----------------
Python (OpenCV, TensorFlow/Keras, PyTorch)

OCR (Tesseract, EasyOCR)

Jupyter Notebook / Google Colab

Django/Flask for deployment

Author:
-------
Posham Chanikya
