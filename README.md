# Space Debris Detection System

## Overview
This project is an AI-powered space debris detection system that analyzes images and identifies debris using machine learning. The system integrates with a web-based UI built using **React, Vite, and TypeScript**, while the backend leverages **Python and OpenCV** for real-time object detection. 

## Features
- **AI-based debris detection** using machine learning models.
- **Precise bounding boxes** to localize debris while ignoring non-debris objects.
- **Real-time visualization** with React Three.js.
- **Threat level analysis** to assess collision risks.
- **User-friendly interface** for uploading and analyzing images.

## Tech Stack
### Frontend:
- React, Vite, TypeScript
- Tailwind CSS for UI styling
- Three.js (`@react-three/fiber`) for 3D visualization

### Backend:
- Python, OpenCV, TensorFlow
- Flask/FastAPI for API endpoints
- YOLO/Faster R-CNN for debris detection

## Installation
### Prerequisites
- Node.js & npm
- Python 3.x
- Virtual environment (optional but recommended)

### Setup Frontend
```sh
cd project
npm install
npm run dev
```

### Setup Backend
```sh
cd backend
pip install -r requirements.txt
python app.py
```

## Usage
1. Upload an image containing space debris.
2. The AI model processes the image and returns detected debris.
3. The frontend displays bounding boxes and relevant information.

## Future Enhancements
- Implement real-time video processing.
- Improve AI accuracy with more training data.
- Add an alert system for critical debris detections.

## Contributing
Feel free to fork this repository, submit issues, or contribute via pull requests!

---
🚀 **Developed for Techxcelerate Hyderabad March Edition, BITS Pilani**

