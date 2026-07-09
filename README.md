# 🐔 FarmVision

An AI-powered computer vision project built using **YOLO** for detecting and identifying farm animals from images. FarmVision is designed to assist with livestock monitoring by automatically recognising animals in real-time.

> **Current Model:** Chicken Detection 🐓

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

The model has been trained to recognise **chickens** with strong detection performance.

### Training Metrics

Add your training results here:

```text
images/train_results.png
```

```markdown
![Training Results](images/train_results.png)
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

## 🖼️ Example Predictions

### Chicken Detection

```markdown
![Prediction 1](images/prediction1.jpg)

![Prediction 2](images/prediction2.jpg)

![Prediction 3](images/prediction3.jpg)
```

These images demonstrate successful detection of chickens using the trained YOLO model.

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

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome.

Feel free to fork the repository, open an issue, or submit a pull request.

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**NupeCoder**

GitHub: https://github.com/NupeCoder
