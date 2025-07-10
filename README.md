# Real-Time Queue Monitoring at ASU Campus Eateries using Computer Vision (YOLOv8)

This project implements a real-time wait time monitoring system for high-traffic campus eateries at Arizona State University using a privacy-preserving computer vision model. By leveraging YOLOv8 for people detection, it estimates live queue lengths and predicts wait times to improve student experience and operational efficiency.

## 🚀 Project Overview

Students at ASU often face long and unpredictable wait times at popular eateries like Chick-fil-A, Starbucks, and Pitchforks. Our system uses overhead cameras and a YOLOv8-based object detection model to count people in queues and estimate real-time wait durations.

## 🎯 Objectives

- Detect and count customers in eatery queues using CV (YOLOv8)
- Estimate and display real-time wait times
- Integrate insights with the ASU mobile app and on-campus digital signage
- Ensure privacy: no facial recognition or identity tracking

## 🛠️ Tech Stack

- **Model**: YOLOv8 (Ultralytics)
- **Language**: Python
- **Tools**: OpenCV, LabelImg, Pandas, NumPy
- **Deployment**: AWS EC2 (for model training), ASU backend (integration)
- **Data**: Custom-labeled cafeteria queue images (~3,000 images)

## 📊 Key Features

- ✅ Real-time people detection in queues
- ✅ Predictive wait-time estimation per eatery
- ✅ Integration-ready for live student-facing platforms
- ✅ Lightweight and privacy-friendly CV model
- ✅ Continuous feedback loop and semester-based retraining

## 📸 Sample Dataset

- Cafeteria queue images captured at various ASU locations (Starbucks, Chick-fil-A, etc.)
- Annotated with bounding boxes around individuals (single class: person)
- Data preprocessed to 640x640 resolution, privacy preserved

## 📈 Model Performance

- Average wait time per customer: ~29.2 seconds
- YOLOv8 fine-tuned on queue-specific data
- Pilot testing showed high correlation between predicted and actual queue lengths


## 📌 Limitations & Future Work

- Plans to upgrade to instance segmentation models (e.g., Mask R-CNN)
- Expansion to other campus services (gyms, libraries, events)


## 📎 References

- [YOLOv8 by Ultralytics](https://github.com/ultralytics/ultralytics)
- [CrowdVision](https://crowdvision.com/solutions-airports/)
- [Queue Monitoring Use Cases](https://www.ultralytics.com/blog/revolutionizing-queue-management-with-ultralytics-yolov8-and-openvino)

---



