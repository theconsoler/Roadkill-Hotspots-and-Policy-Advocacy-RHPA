# 🦌 Roadkill Hotspots and Policy Advocacy (RHPA)

## 📌 Overview
Roadkill incidents are a major concern for both wildlife conservation and road safety.  
The **RHPA project** uses AI and computer vision to detect, track, and analyze animals crossing roads. It identifies risk zones, estimates animal speed, and sends real-time alerts to help prevent accidents.  

This project aims to provide **data-driven insights** for **wildlife protection** and **policy advocacy**.

---

## 🚀 Features
- **YOLOv5xu Animal Detection** – Identifies animals (cats, dogs, deer, cows, etc.) in real-time.
- **Optical Flow Analysis** – Detects motion to classify animals as *Alive* or *Potentially Dead*.
- **Risk-Level Classification** – Highlights *High, Medium, and Low* risk zones based on animal position.
- **Speed Estimation** – Calculates animal movement speed in km/h.
- **Real-Time Alerts** – Triggers sound warnings or API-based notifications when animals enter danger zones.
- **Video Processing** – Saves processed videos with bounding boxes, motion labels, and risk tags.
- **Gradio Interface** – Simple web-based UI for uploading dashcam videos and reviewing processed results.
- **Optimizations** – GPU acceleration, frame skipping, resolution scaling for faster inference.

---

## 🛠️ Tools & Libraries Used
- **YOLOv5xu (Ultralytics)** – Pre-trained model customized for animal detection.
- **Optical Flow (Farneback method)** – Motion detection and tracking.
- **OpenCV** – Video frame processing and bounding box visualization.
- **NumPy & Matplotlib** – Numerical operations and result visualization.
- **Gradio** – User-friendly interface for interactive testing.
- **PyTorch** – Deep learning framework for running YOLOv5xu models.
- **GPU Acceleration (CUDA)** – For faster inference when available.

---

## 🎯 Why I Built This
- To **reduce wildlife casualties** and support **road safety**.  
- To create a **scalable AI system** that can integrate with **dashcams and traffic monitoring systems**.  
- To provide **evidence-based insights** that can help shape **policy advocacy for wildlife protection**.  

---

## 📂 Future Enhancements
- Real-time live dashcam feed monitoring.
- IoT integration for instant roadside alerts.
- Reinforcement learning for adaptive risk assessment.
- Multi-camera fusion for larger road coverage.

---

## 📸 Example Output
- Bounding boxes with labels (*Alive / Potentially Dead*).
- Risk classification (*High, Medium, Low*).
- Speed estimation displayed in km/h.
- Alerts shown when high-risk animals are detected.

---

## 📚 References
- [YOLOv5 by Ultralytics](https://github.com/ultralytics/yolov5)  
- Optical Flow research papers & motion detection methods.  
- OpenCV for real-time computer vision.  

---

## 🧑‍💻 Author
Developed by **[PIYUSH KUMAR SAHOO]**  
Cybersecurity & AI Enthusiast | Focused on real-world applications of computer vision in safety and conservation.  

