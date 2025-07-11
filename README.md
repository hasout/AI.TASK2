
# Face Recognition using OpenCV

## Description
This project uses OpenCV and face_recognition libraries to detect and recognize faces from a webcam feed in real time.

## Features
- Detects known and unknown faces
- Uses webcam as input
- Real-time recognition and labeling

## Requirements
- Python 3.x
- OpenCV
- face_recognition
- numpy

## Installation

```bash
pip install -r requirements.txt
```

## Usage
1. Add known faces in the `known_faces/` folder.
2. Rename images as `name.jpg`.
3. Run the program:

```bash
python face_recog.py
```

4. Press `Q` to quit.


## Notes
- You can add more images for better recognition accuracy.
- Make sure lighting is good when using webcam.
