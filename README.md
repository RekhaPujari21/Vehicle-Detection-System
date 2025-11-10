# Vehicle Detection & Counting System

This project is a real-time and video-based Vehicle Detection & Counting System built using YOLO, OpenCV, and Streamlit. It detects vehicles inside a user-defined ROI and counts them by category.

## Features
- Upload video or use live camera feed
- Detects and counts 4 types of vehicles:
  - Two Wheeler (Bikes, Scooters, Cycles)
  - Auto (Three Wheeler)
  - Four Wheeler (Cars, Mini Trucks, Taxi)
  - Large Vehicles (Lorry, Trucks, Tanker)
- User-defined ROI (x1, y1, x2, y2)
- Saves processed output video
- Live real-time display using Streamlit

## Tech Stack
- Python
- YOLO (Ultralytics)
- OpenCV
- NumPy
- Streamlit

## Project Structure
project/
│── app.py  
│── videos/  
│     └── (uploaded videos saved here)  
│── runs/  
│     └── detect/  
│          └── train/  
│               └── weights/  
│                    └── best.pt  

## How to Run

### 1. Install dependencies

### 2. Place your trained YOLO model
Add your model here:

### 3. Create videos folder

### 4. Run the Streamlit app

## ROI Format
Enter coordinates like:x1,y1,x2,y2

Example:0,0,1280,720

## Output
- For uploaded videos: processed video saved with bounding boxes and counts
- For live camera: real-time display inside Streamlit

## Future Improvements
- Speed estimation
- Tracking IDs
- Analytics dashboard
- Multi-camera support
