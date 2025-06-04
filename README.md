# 🏗️ Construction Progress Monitoring using ML | SIH 2024

This project was developed for **Smart India Hackathon 2024** under problem statement ID **1725**:  
**"Utilization of images for monitoring of progress of construction activities for building construction projects."**

## 🚀 Solution Overview

We developed a software system that leverages **computer vision** and **deep learning** (YOLOv8, SSIM, etc.) to automate the **remote monitoring** of construction progress using images.

---

## 🛠️ Tech Stack

| Task | Technology |
|------|------------|
| Object Detection | YOLOv8 (Ultralytics) |
| Preprocessing | OpenCV, Pillow |
| Deep Learning | PyTorch, TensorFlow, Keras |
| Classification | Scikit-learn |
| Web Framework | Django, React |
| Storage | MongoDB |
| Deployment | Docker, Kubernetes, Google Colab |

---

## 🔍 Features

- Detect key construction stages (e.g., foundation, walls, interiors).
- Track progress using **image difference (SSIM)**.
- Validate and flag errors in input images.
- Real-time image upload via web interface.
- Scalable backend using containerized microservices.

---

## 💡 Innovation

- Custom tracking of specific tasks like **window installation**.
- Error-checking for mismatched or invalid image inputs.
- Detailed UI with visual progress reports.

---

## 📂 Folder Breakdown

| Folder | Description |
|--------|-------------|
| `yolov8_model/` | Training & inference code for YOLOv8 |
| `webapp/` | UI components (React + Django backend) |
| `utils/` | SSIM, preprocessing scripts |
| `sample_images/` | Sample input-output images |
| `SIH_Final_presentation.pdf` | Submission document |

---

## 🔗 References

- [YOLOv8 (Ultralytics)](https://github.com/ultralytics/ultralytics)
- [OpenCV](https://opencv.org/)
- [TensorFlow](https://www.tensorflow.org/)
- [PyTorch](https://pytorch.org/)
- [SSIM paper](https://en.wikipedia.org/wiki/Structural_similarity)

---

## 👥 Team

Team Name: **The Outliers**  
Submitted to **Smart India Hackathon 2024**

---

