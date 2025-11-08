# License Plate Recognition (LPR) System

## Overview
This project implements a license plate recognition (LPR) system designed to recognize Chinese license plates using a combination of computer vision techniques and the Tesseract OCR engine. The system detects and extracts the province and alphanumeric characters from the license plate, which is essential for various applications like traffic monitoring and vehicle tracking.

## Features
- **Plate Detection**: Identifies the region of interest (ROI) corresponding to the license plate in an image.
- **Province Recognition**: Extracts the province character from the left side of the plate.
- **Character Recognition**: Uses Tesseract OCR to recognize the characters and numbers on the plate.
- **Image Pre-processing**: Includes color-based segmentation and geometric analysis to enhance recognition accuracy.
- **OCR Corrections**: Corrects common character misreadings (e.g., "O" to "0", "I" to "1").

## Requirements
- Python 3.x
- OpenCV
- Numpy
- Tesseract OCR
- Pillow (PIL)
- Math module

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/carpanel_recognition.git

