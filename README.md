# Your-Eyes

## 🚀 Project Features
Your Eyes is an AI-powered assistive system (software prototype) designed to help blind and visually impaired users understand their surroundings through real-time Computer Vision.
The project integrates multiple CV and audio technologies to deliver an accessible, interactive experience.

## 👁️ Image Detection
- Upload an image and automatically analyze its content
- Detect and classify objects using YOLOv8
- Return object names, confidence scores, and bounding boxes
- Provide optional audio narration of detected objects

## 🎥 Video Detection
- Upload a video for frame-by-frame object detection
- Real-time overlay of bounding boxes and labels on each frame
- Smooth simultaneous playback + detection inside the Streamlit app
- Support for different video formats

## 📷 Real-Time Webcam Detection
- Activate your device’s webcam for live Object Detection
- Real-time visualization of detected objects
- Continuous audio feedback to describe the scene to the user
- Designed to simulate smart glasses behavior for blind assistance

## 🔊 Text-to-Speech Integration
- Convert detection results into spoken guidance
- Provide scene description and object names vocally
- Allows hands-free interaction, improving accessibility

## 🖥️ User-Friendly Interface (Streamlit)
- Clean and intuitive UI for interacting with all features
- Tabs for: Image Detection, Video Detection, Webcam Mode, and Settings
- Smooth model loading and fast inference experience


## 🛠️ Used Tech Stack
Languages:
Python 3.10 (Core development)

Frameworks & Tools:
YOLOv8 (Ultralytics) – Object detection model
Streamlit – GUI frontend
OpenCV – Image & video processing
PyTorch – Deep learning backend
TTS – Text-to-Speech engine

