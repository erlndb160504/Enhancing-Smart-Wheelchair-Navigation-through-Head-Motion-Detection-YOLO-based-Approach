# Smart Wheelchair Navigation using YOLO

## Overview
This project presents a **smart wheelchair navigation system** that leverages **YOLO-based head motion detection** to assist individuals with physical disabilities. The system uses a camera to detect head movements and translates them into navigation commands, providing a hands-free mobility solution.

## Features
- **Head Movement Detection**: Utilizes deep learning models (YOLOv5, YOLOv6, and YOLOv7) to recognize four movement directions: front, down, left, and right.
- **Real-Time Processing**: Ensures fast inference time for smooth navigation.
- **Comparative Model Evaluation**: Assesses the performance of different YOLO variants based on inference speed and accuracy.
- **Potential for Future Enhancements**: Supports the integration of multimodal sensors such as infrared (IR) or depth cameras for improved performance in low-light conditions.

## Dataset
The dataset consists of **2,224 images** labeled into four classes: `front`, `down`, `left`, and `right`. The dataset is publicly available at:
[Dataset Link](https://universe.roboflow.com/pkm-celia/deteksi-arah-gerak-kepala)

## Model Comparison
The system evaluates different YOLO versions based on:
- **Inference Time**: YOLOv6N achieved the fastest inference time (2.54 ms).
- **Detection Accuracy**: All YOLO variants demonstrated a high **precision and recall (>0.9)**.
- **mAP Score**: YOLOv6L achieved the highest **mAP@.5:.95 score of 0.808**.


## Installation & Setup
### Prerequisites
- Python 3.8+
- PyTorch
- OpenCV
- Roboflow API (for dataset access)
- Arduino IDE (for motor control integration)

- # Future Work
- Implement **transfer learning** to enhance adaptability for different disabilities.
- Integrate **infrared (IR) sensors and depth cameras** for improved detection in low-light conditions.
- Develop an **adaptive filtering mechanism** to reduce unintentional head movements.

## Authors
- **Fitri Utaminingrum** – Supervisor, Review
- **Erlinda Butarbutar** – Electrical System, Integration
- **Rahma Nur Fitriyani** – Requirements Engineering
- **Yvette Celia Aviani** – Deep Learning, Model Training
- **Atik Qomariyah** – Ethics Testing, Review

## Acknowledgments
This research was supported by **Universitas Brawijaya**. Special thanks to our mentors and collaborators for their valuable insights.

## License
This project is licensed under the **MIT License**.

---
