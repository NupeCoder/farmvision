# 🐔 FarmVision

An AI-powered computer vision project built using **YOLO** for detecting and identifying farm animals from images. FarmVision is designed to assist with livestock monitoring by automatically recognising animals in real-time.

Chicken Dataset - https://universe.roboflow.com/liangyingying-ugu8c/chicken-counting-wifqp-b56zo/dataset/1

> **Current Model:** Chicken Detection 🐓

<img width="1920" height="1100" alt="val_batch0_pred" src="https://github.com/user-attachments/assets/2e82f022-3e97-4a54-a9ea-406cdde43f1b" />

<img width="1920" height="1920" alt="train_batch1" src="https://github.com/user-attachments/assets/b59e4f6a-aaa4-4599-8b5e-344b3fe6da18" />

*NOTE* 
Code and files have been ommitted from the time being as development continues and can be shared on request

---

## 📖 Overview

FarmVision is a machine learning project that uses the **YOLO (You Only Look Once)** object detection model to identify farm animals within images.

The current version has been trained to detect **chickens**, with future plans to support additional farm animals such as:

* 🐄 Cows
* 🐑 Sheep
* 🦆 Ducks
* 🐐 Goats

The aim of this project is to provide a foundation for automated livestock monitoring that could be expanded into smart farming applications.

---

## 🚀 Features

* Real-time object detection using YOLO
* Chicken detection with bounding boxes
* Confidence score for each prediction
* Easy to extend with additional animal classes
* Custom-trained dataset
* Model evaluation with performance metrics

---

## 🛠️ Technologies Used

* Python
* YOLO
* OpenCV
* Ultralytics
* NumPy
* Matplotlib

---

## 📂 Project Structure

```text
farmvision/
│
├── dataset/           # Training and validation images
├── models/            # Trained YOLO weights
├── runs/              # Training results
├── images/            # Example predictions & README assets
├── notebooks/         # Training notebooks (if applicable)
├── requirements.txt
└── README.md
```

---

## 📊 Model Performance

The current YOLO model has been trained to detect **chickens** and demonstrates consistent improvements throughout training.

### Final Performance Metrics

| Metric | Result |
|---------|--------|
| Precision | **84.5%** |
| Recall | **74.5%** |
| mAP@50 | **82.5%** |
| mAP@50-95 | **45.0%** |

These metrics indicate that the model can reliably identify chickens in images while maintaining a strong balance between precision and recall.

---

## 📈 Future Improvements

* Add support for multiple farm animal classes
* Increase dataset size
* Improve detection accuracy
* Live webcam detection
* Video processing
* Deploy as a web application
* Mobile-friendly inference

---

## 🎯 Project Goals

* Learn and apply modern object detection techniques
* Build a scalable livestock detection system
* Explore real-world agricultural AI applications
* Create a reusable model that can expand to additional farm animals

---

## 👨‍💻 Author

**NupeCoder**

GitHub: https://github.com/NupeCoder
