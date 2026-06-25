# Plant Counting and Localization Using YOLOv11s

## Project Overview

This project presents a deep learning-based approach for detecting and localizing banana plants from UAV (drone) images using the **YOLOv11s Object Detection** model. The system automatically identifies banana plants by drawing bounding boxes around each detected plant, reducing manual effort and supporting precision agriculture.



## Objectives

- Detect banana plants from UAV images.
- Localize each detected plant using bounding boxes.
- Improve detection accuracy using the YOLOv11s model.
- Support precision agriculture through automated plant monitoring.



## Technologies Used

- Python
- Google Colab
- YOLOv11s (Ultralytics)
- Roboflow
- OpenCV
- NumPy
- Matplotlib



## Dataset Details

 Training - 161 
 Validation - 20 
 Testing - 21 
 Total - 202

Annotation Tool: Roboflow

Annotation Type:Bounding Boxes



##  Model Used

**YOLOv11s Object Detection**

YOLOv11s was selected because it provides:
- High detection accuracy
- Fast inference speed
- Lightweight architecture
- Low computational cost
- Suitable for real-time UAV applications



## Training Configuration

 Model - YOLOv11s 
 Image Size - 640 × 640
 Training Images - 161 
 Validation Images -  20 
 Test Images - 21 



## Model Performance

Precision - 96.0% 
 Recall - 96.5% 
 mAP@50 - 98.2% 
 mAP@50-95 - 92.8% 



##  Sample Results

The trained YOLOv11s model successfully detects and localizes banana plants using bounding boxes.

##  Project Workflow

1. UAV Image Collection
2. Image Preprocessing
3. Image Annotation using Roboflow
4. YOLOv11s Model Training
5. Object Detection
6. Plant Localization
7. Performance Evaluation


## 🔮 Future Scope

- Detect multiple crop types.
- Estimate crop density.
- Integrate disease detection.
- Deploy the model on UAVs for real-time monitoring.



##  Author

Amirtha B


## 📄 License

This project is licensed under the MIT License.
