# Violence-Detection 

`violence-detection` uses YOLOv8n.pt and a Roboflow dataset to detect violent actions in real-time video, with a Tkinter UI. Built at zero cost on donated hardware, it achieves 80%+ accuracy for enhancing safety.

## Overview

This project aims to reduce societal violence by detecting aggressive incidents in real-time using YOLOv8n.pt and a Roboflow dataset. It identifies violent actions (e.g., attacks) versus non-violent ones, triggering alerts for swift intervention. Trained on diverse data, the system ensures accuracy across settings like schools or public spaces, leveraging a Tkinter UI for monitoring—all at zero cost.

## Output Example

![Detection Output](output-example.png)  
*Red bounding box marks a violent action detected in a sample frame.*


## Modules

- **Data Collection**: Sources balanced Roboflow dataset (50% violent, 50% non-violent).  
- **Pre-processing**: Splits videos into 150 frames at 640x640, augmented for diversity.  
- **Training**: Fine-tunes YOLOv8n.pt on donated GPUs.  
- **Backend**: Processes live feeds with trained YOLO model.  
- **UI**: Tkinter displays red (violence) and green (non-violence) boxes.

## Output Example

![Detection Output](output-example.png)  
*Red bounding box shows a detected violent action.*


## Install Dependencies

Requires Python 3.x, OpenCV, and Ultralytics YOLOv8—all free.  

```bash
pip install opencv-python ultralytics
