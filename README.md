# Crowd Detection and Counting in Movie Scenes using YOLOv8

This project aims to detect and count crowds in movie scenes using the YOLOv8 object detection model. The notebook performs a full workflow from video data preparation to applying a deep learning model and visualizing the results.

## 🧠 Project Objective

To implement a deep learning pipeline for detecting and counting people in movie scenes, leveraging the power of the YOLOv8 object detection architecture. The goal is to:

- Analyze crowded scenes in movies
- Automate person detection in each frame
- Count the number of people detected
- Visualize and save the results for further analysis

---

## 📁 Files

- `crowd_detection_yolov8.ipynb`: Main Jupyter notebook containing all the code for crowd detection and counting using YOLOv8.

---

## ✅ Tasks Performed

### 1. **Environment Setup**
- Installed required libraries including Ultralytics' YOLOv8.
- Verified GPU availability for efficient model inference.

### 2. **Loading YOLOv8 Model**
- Loaded a pretrained YOLOv8 model (`yolov8n.pt` or similar).
- Configured model settings such as confidence threshold and image size.

### 3. **Video Input and Frame Extraction**
- Read input video clips or GIFs from movie scenes.
- Extracted individual frames from the video for processing.

### 4. **Crowd Detection**
- Used YOLOv8 to detect people in each frame.
- Drew bounding boxes and labels for each detected person.

### 5. **Crowd Counting**
- Counted the number of detected persons in each frame.
- Stored frame-wise count data for later use.

### 6. **Visualization and Output**
- Annotated frames with detection boxes and count overlays.
- Compiled processed frames into a video or GIF for visualization.
- Optionally saved outputs (images/videos) to disk.

### 7. **Performance Optimization**
- Enabled GPU acceleration where available.
- Batched frame processing for improved speed (if applicable).

---

## 🛠️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/crowd-detection-yolov8.git
   cd crowd-detection-yolov8
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook:
   - Open `crowd_detection_yolov8.ipynb` in Jupyter.
   - Run all cells step by step.

---

## 📊 Example Output

- Video with bounding boxes around detected people.
- Frame-by-frame count of people displayed on the screen.
- Optionally: CSV or chart with time-series of crowd count.

---

## 🔍 Future Enhancements

- Annotate data and fine-tune YOLOv8 on movie-specific scenes for better accuracy.
- Integrate tracking to maintain identities across frames.
- Add dashboard for interactive visualization of detection stats.

---
