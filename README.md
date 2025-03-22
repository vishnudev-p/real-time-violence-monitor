# violence-detection

`violence-detection` uses YOLOv8n.pt and a Roboflow dataset to detect violent actions in real-time video, with a Tkinter UI. Built at zero cost on donated hardware, it achieves 80%+ accuracy for enhancing safety.

## Features

- Real-time violence detection with YOLOv8n.pt model
- Trained on a balanced Roboflow dataset (50% violent, 50% non-violent)
- Tkinter UI with red (violence) and green (non-violence) bounding boxes
- Zero-cost implementation using open-source tools and donated hardware
- Over 80% accuracy, 15-30 FPS on modest systems

## Output Example

Below is a sample output of the system in action:

![Violence Detection Output](output-example.png)  
*Red bounding box highlights a detected violent action (e.g., a punch) on the live feed.*

## Installation

1. **Clone the Repository**  
   ```bash
   git clone https://github.com/yourusername/violence-detection.git
   cd violence-detection

Install Dependencies
Requires Python 3.x, OpenCV, and Ultralytics YOLOv8—all free.
bash

Collapse

Wrap

Copy
pip install opencv-python ultralytics
Tkinter comes with Python; no separate install needed.
Connect a webcam or camera to your donated hardware.
Model Weights
Download YOLOv8n.pt from Ultralytics or fine-tune with your Roboflow dataset (see train.py).
Usage
Run the System
bash

Collapse

Wrap

Copy
python violence_detection.py
Opens the Tkinter UI with live video.
Click "Start" to detect; "Stop" to pause.
Interpret Results
Red boxes = violent actions; green boxes = non-violent.
Alerts pop up for violence detections.
Requirements
Hardware: Donated PC or Raspberry Pi with a camera
Software: Python 3.6+, Ubuntu (or similar), OpenCV 4.x, Ultralytics YOLOv8
Dataset: Roboflow free-tier dataset (violence/non-violence)
Contributing
Fork the repo, make improvements, and submit a pull request. Welcome contributions in model optimization, UI upgrades, or dataset expansion—all zero-cost.

