# Threat-Detection-System
A custom-trained YOLOv5 model designed to detect threats such as handguns, assault rifles, and knives with high accuracy. Trained on a tailored dataset, this system achieves 82% validation accuracy and supports detection in pre-recorded videos, real-time webcam streams, and image directories. Optimized for performance, it delivers ~10 FPS on a CPU and 25+ FPS using a GPU with CUDA.
## Project Summary
This project utilizes a custom-trained YOLOv5 deep learning model to detect potential threats such as handguns, assault rifles, and knives. With 82% validation accuracy, the model has been optimized for detecting threats in pre-recorded videos, achieving approximately:

- 20 FPS on a CPU.
- 45+ FPS on a GPU with CUDA support.

## Features
- Real-Time Detection: Capable of analyzing webcam streams for live threat detection.
- Custom Dataset: Trained on a tailored dataset of weapons for high accuracy.
- Flexible Inference: Supports video files, webcam input, or directory images.

## Repository Contents
- detect.py: Modified YOLOv5 detection script for live camera feed.
- Trained Model (best.pt): Pre-trained weights for the threat detection system.
- Jupyter Notebook: A notebook for running the detection script in Python.
- README.md: Documentation for setup and usage.

## How to Use
1. Clone the Repository
2. Install Requirements (Prefferably in a new virtual environment)
3. Run the Detection Script
You can use either of the following methods to run the model:

	- **Command-Line Interface (CLI):**   ```python detect.py --weights yolov5\runs\train\exp\weights\best.pt --source <path-to-video.mp4>```<br>
	- **Jupyter Notebook:** Open the provided Jupyter Notebook and follow the instructions to run the detection script interactively.


## Performance Metrics
- Validation Accuracy: 82%
- Inference Speed: ~20 FPS (CPU), 45+ FPS (GPU with CUDA)

## Results
https://github.com/user-attachments/assets/d0594b5a-da60-405d-98d3-9d8115c7f4b9


