# Brain Tumor Detection and Classification (DBV)

## Overview  
The **Deep Brain Vision (DBV)** project leverages deep learning and computer vision techniques to enhance the detection and classification of brain tumors from MRI scans. The system integrates **YOLOv8/YOLOv11** for tumor detection and **ResNet50** for classification, providing a real-time solution for medical image analysis.

## Methodology  
1. **Data Acquisition** – MRI scans are collected and prepared.  
2. **Preprocessing & Augmentation** – Images are enhanced and transformed.  
3. **Tumor Detection (YOLOv8 / YOLOv11)** – Identifies tumors with bounding boxes.  
4. **Feature Extraction & ROI Processing** – Extracts tumor regions for classification.  
5. **Classification (ResNet50)** – Determines tumor type (e.g., Meningioma, Glioma).  
6. **Deployment with Flask** – Enables real-time model inference through a web interface.  

![Methodology](https://github.com/Rehab-Alsaidi/DBV-/blob/main/DBV_Methodology.png?raw=true) 

## Model Evolution & Performance  

### **YOLOv8n (Initial Model - 2024)**  
| Metric  | Value  |  
|---------|--------|  
| Precision | 0.939  |  
| Recall  | 0.930  |  
| mAP 50  | 0.964  |  
| mAP 50-95  | 0.610  |  

### **YOLOv11n (Improved Model - 2025)**  
| Metric  | Value  |  
|---------|--------|  
| Precision | 0.988  |  
| Recall  | 0.982  |  
| mAP 50  | 0.993  |  
| mAP 50-95  | 0.777  |  

### **ResNet50 (Tumor Classification Results)**  
| Metric  | Value  |  
|---------|--------|  
| Accuracy | 0.95  |  
| Precision | 0.9493  |  
| Recall  | 0.9492  |  
| F1 Score  | 0.9489  |  

## Results  
The latest **YOLOv11n + ResNet50** model integration significantly improves detection and classification accuracy, providing **a robust AI-driven tool for brain tumor diagnosis**.  



## Deployment  
- **Framework:** Flask  
- **Models Used:** YOLOv11 for detection, ResNet50 for classification  
- **Output:** Web interface for MRI tumor detection and classification
![Results](https://github.com/Rehab-Alsaidi/DBV-/blob/main/Flask.png?raw=true)

## Conclusion  
DBV demonstrates the potential of AI in medical diagnosis, improving accuracy and efficiency in brain tumor detection. The system offers **real-time inference**, **high precision**, and **automated tumor classification**, making it a valuable tool for radiologists.  

