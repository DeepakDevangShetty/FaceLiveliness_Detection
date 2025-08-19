# Face Liveliness Detection

## 📌 Project Description
This project focuses on developing a **Face Anti-Spoofing System** that integrates **camera-based depth estimation** with **sensor fusion (IMU, facial landmarks, and pose cues)** to differentiate between real human faces and spoofing attempts (such as photos, videos, or 3D masks). By leveraging **deep learning models** and **computer vision techniques**, the system enhances security for facial authentication in mobile and embedded devices.

---

## 🎯 Objectives
- Detect spoofing attempts in facial authentication systems.
- Integrate **depth cues from cameras** and **IMU sensor data** for robust classification.
- Train lightweight models deployable on **mobile and edge devices**.
- Improve reliability of face recognition systems in **real-world conditions**.

---

## 📚 Background & Related Work
Traditional face authentication systems are highly vulnerable to spoofing attacks using printed photos, videos, or 3D masks. While some solutions rely only on RGB images, they often fail in diverse environments.  
This project builds upon existing research in:
- **Depth estimation** for distinguishing flat surfaces from real 3D faces.  
- **Sensor fusion** (IMU and pose cues) for enhanced liveness detection.  
- **Lightweight deep learning** for mobile deployment.  

---

## 🔍 Analysis of Problem Statement
- Spoofing attacks remain a critical challenge in biometric authentication.  
- Most systems fail to generalize in uncontrolled environments.  
- Depth-based + sensor-fusion approaches show promise but lack **efficient mobile deployment**.  
- This project addresses these gaps by building a **robust, optimized, and deployable solution**.  

---

## 💡 Innovation / Novel Contributions
- **Depth-based Anti-Spoofing** integrated with **facial landmarks and pose analysis**.  
- Use of **IMU sensors** for real-time liveness detection.  
- Deployment-ready lightweight models optimized with **TFLite / ONNX Runtime**.  
- Enhanced accuracy in detecting **photo/video replay and 3D mask attacks**.  

---

## 🛠️ Technology Stack
- **Programming & Frameworks:** Python, PyTorch / TensorFlow  
- **Model Deployment:** TensorFlow Lite, ONNX Runtime  
- **Computer Vision:** OpenCV, Dlib, Mediapipe  
- **Data Handling:** NumPy, Pandas, Matplotlib, Seaborn  
- **Collaboration & Version Control:** Git, GitHub  
- **Optimization:** TensorFlow Model Optimization Toolkit, TFLite Converter  


---

## 📖 References
- [Face Anti-Spoofing with Depth Maps](https://arxiv.org/abs/1904.02860)  
- [Mediapipe Face Detection](https://developers.google.com/mediapipe/solutions/vision/face_detection)  
- [ONNX Runtime](https://onnxruntime.ai/)  
- [TensorFlow Lite](https://www.tensorflow.org/lite)  
- [OpenCV](https://opencv.org/)  

---
