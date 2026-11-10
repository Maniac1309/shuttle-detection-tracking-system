# Shuttle Detection and Tracking System

YOLOv8-based shuttlecock detection and tracking system built with FastAPI and JavaScript.

## Features

- Shuttle detection on images
- Shuttle tracking on videos
- FastAPI backend
- Interactive frontend
- MP4 output generation

## Tech Stack

- Python
- FastAPI
- Ultralytics YOLOv8
- JavaScript
- HTML/CSS
- FFmpeg

## Run Backend

```bash
cd backend
uvicorn app:app --reload
```

## Run Frontend

Open frontend/index.html using Live Server.

## API Endpoints

POST /predict

POST /track