# License Plate Recognition System

## Overview
The License Plate Recognition (LPR) System is a computer vision project designed to automatically detect and recognize license plates from images and video streams. This system processes video frames in real-time, detecting vehicles, identifying license plates, and extracting alphanumeric characters for further processing. It leverages deep learning and tracking algorithms to ensure accurate detection and recognition.

## Features
- **Real-time Detection:** Identifies vehicles and license plates from video streams.
- **License Plate Recognition:** Extracts alphanumeric characters from detected plates.
- **Vehicle Association:** Matches detected plates with their respective vehicles.
- **Custom Model Training:** Utilizes a custom-trained license plate detection model.
- **Optical Character Recognition (OCR):** Reads plate contents using the PaddleOCR English pretrained model.
- **Vehicle Tracking:** Implements the ByteTrack algorithm for tracking vehicle movement.
- **Data Storage:** Saves detected information for further analysis.

## Technologies Used
- **Python** - Core programming language
- **OpenCV** - For image and video processing
- **YOLO (You Only Look Once)** - Object detection model for vehicle and plate detection
- **PaddleOCR** - For character recognition from license plates
- **ByteTrack** - For vehicle tracking and association

## Training the License Plate Detection Model
The system uses a custom-trained YOLO model for license plate detection. The model was trained on a dataset specifically created for this project, ensuring high accuracy in various lighting and environmental conditions.

## Installation
To set up the project on your local machine:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/ankur-jat0009/License-Plate-Recognition-System.git
   ```
2. **Navigate to the project directory:**
   ```bash
   cd License-Plate-Recognition-System
   ```
3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

## Usage
To run the system and process a video file:

```bash
python main.py -i input_video.mp4 -d
```
- `-i`: Specify the input video file path.
- `-d`: (Optional) Display the output while processing the video.


## Contributions
Contributions are welcome! Feel free to fork the repository, make improvements, and submit a pull request. If you find any issues or have suggestions, open a GitHub issue.


---


