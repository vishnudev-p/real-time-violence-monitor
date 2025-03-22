# violence-detection - Abstract

`violence-detection` uses YOLOv8n.pt and a Roboflow dataset to detect violent actions in real-time video, with a Tkinter UI. Built at zero cost on donated hardware, it achieves 80%+ accuracy for enhancing safety.

## Overview

This project aims to reduce societal violence by detecting aggressive incidents in real-time using YOLOv8n.pt and a Roboflow dataset. It identifies violent actions (e.g., attacks) versus non-violent ones, triggering alerts for swift intervention. Trained on diverse data, the system ensures accuracy across settings like schools or public spaces, leveraging a Tkinter UI for monitoring—all at zero cost.

## Output Example

![Detection Output](output-example.png)  
*Red bounding box marks a violent action detected in a sample frame.*

# violence-detection - Introduction

`violence-detection` uses YOLOv8n.pt and a Roboflow dataset to detect violent actions in real-time video, with a Tkinter UI. Built at zero cost on donated hardware, it achieves 80%+ accuracy for enhancing safety.

## Overview

Violence poses a persistent societal challenge, straining safety and resources. This project introduces a zero-cost, real-time detection system using YOLOv8n.pt to identify aggressive acts (e.g., punches) in video feeds. With a Tkinter UI and Roboflow-trained model, it automates monitoring on donated hardware, aiming to prevent escalation in settings like schools or streets, surpassing manual surveillance limitations.

## Output Example

![Detection Output](output-example.png)  
*Red bounding box highlights a violent action in a live feed.*

# violence-detection - Module Description

`violence-detection` uses YOLOv8n.pt and a Roboflow dataset to detect violent actions in real-time video, with a Tkinter UI. Built at zero cost on donated hardware, it achieves 80%+ accuracy for enhancing safety.

## Modules

- **Data Collection**: Sources balanced Roboflow dataset (50% violent, 50% non-violent).  
- **Pre-processing**: Splits videos into 150 frames at 640x640, augmented for diversity.  
- **Training**: Fine-tunes YOLOv8n.pt on donated GPUs.  
- **Backend**: Processes live feeds with trained YOLO model.  
- **UI**: Tkinter displays red (violence) and green (non-violence) boxes.

## Output Example

![Detection Output](output-example.png)  
*Red bounding box shows a detected violent action.*

# violence-detection - System Comparison

`violence-detection` uses YOLOv8n.pt and a Roboflow dataset to detect violent actions in real-time video, with a Tkinter UI. Built at zero cost on donated hardware, it achieves 80%+ accuracy for enhancing safety.

## Existing Systems

Manual surveillance and older ML models (e.g., YOLOv3) lack real-time efficiency and scalability, suffering from human error and high resource needs.

## Proposed System

This system uses YOLOv8n.pt, Roboflow data, and Tkinter UI on donated hardware, offering real-time detection (>80% accuracy) at zero cost, outperforming predecessors with scalability and usability.

## Output Example

![Detection Output](output-example.png)  
*Red bounding box marks violence in a sample frame.*

# violence-detection

`violence-detection` uses YOLOv8n.pt and a Roboflow dataset to detect violent actions in real-time video, with a Tkinter UI. Built at zero cost on donated hardware, it achieves 80%+ accuracy for enhancing safety.

## Install Dependencies

Requires Python 3.x, OpenCV, and Ultralytics YOLOv8—all free.  

```bash
pip install opencv-python ultralytics
