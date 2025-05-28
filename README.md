
# Classification of Common Rice Diseases Using Deep Learning Models

## Introduction
This is a graduation thesis applying **Artificial Intelligence (AI)** and **Deep Learning** to identify and segment disease areas on rice leaves through images, aiming to support early diagnosis and smart agriculture. The project employs two state-of-the-art models:

- **YOLOv8-seg** by Ultralytics
- **Mask R-CNN** by Detectron2 (Facebook AI Research)

## Objectives
- Build an image dataset of 4 common rice diseases:
  - Rice blast
  - Bacterial leaf blight
  - Organic toxicity
  - Grain discoloration
- Apply deep learning models to accurately segment disease-affected regions on rice plant images.
- Evaluate model performance using metrics like Precision, Recall, IoU, and mAP.

## Technologies & Libraries Used
- Programming language: **Python**
- Deep learning framework: **PyTorch**
- Training environment: **Kaggle Notebooks**
- Data processing tool: **Roboflow**
- Models:
  - YOLOv8 (Ultralytics)
  - Mask R-CNN (Detectron2)
- Dataset: Collected from two real rice fields in An Giang Province, Vietnam.

## Model Illustration

| YOLOv8-seg Segmentation | Mask R-CNN Segmentation |
|--------------------------|---------------------------|
|![image](https://github.com/user-attachments/assets/0e868d4f-3070-4f2a-82ff-d29edc012c70) | ![image](https://github.com/user-attachments/assets/3d24e0eb-693c-419d-b859-fd514bccd992)

## Experimental Results
- **YOLOv8-seg**: Faster inference speed, suitable for real-time applications.
- **Mask R-CNN**: Higher segmentation quality, but slower.
- Both models struggled with class imbalance and small object detection.

## Future Development
- Improve class balance in the training data.
- Apply lightweight models for mobile or embedded devices.
- Develop real-time rice disease monitoring systems in the field.

## Author
- **Student**: Nguyễn Nhật Tinh Anh
- **Supervisor**: Dr. Nguyễn Văn Hòa
- **University**: An Giang University – Faculty of Information Technology

## License
All rights reserved by the author and An Giang University. This project is for research and educational purposes only.
