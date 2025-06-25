# 🔥 Invisible/Fire Detection System using YOLOv8 (Colab Notebook)

An AI-based fire detection system built entirely in a Google Colab notebook. It uses the YOLOv8 object detection model to identify fire in real-time from a webcam or video input. The system is lightweight, easy to set up, and can be extended with thermal filtering and IoT device integration.

---

## 🚀 Features

- 🔍 Real-time fire detection using webcam or video
- 🤖 Fine-tuned YOLOv8 model on fire datasets
- can detect invisible flames
- ⚙️ Runs entirely on Google Colab (no setup needed!)
- 📸 Supports webcam access using Colab + JavaScript hack
- 🔔 Logs fire detection and can be extended with alert systems
- 🧠 Future-ready for thermal-style filtering and ESP32 integration

---

## 🛠️ Tech Stack

- **Python**
- **YOLOv8 (Ultralytics)**
- **OpenCV** – for real-time video processing
- **Google Colab** – GPU-powered training and testing
- *(Planned)* ESP32 + GPIO alert system

---

## 📓 How to Use

1. Open the notebook:  
   👉 [**Click here to open the Fire Detection Notebook**]  

2. Follow the cells step-by-step:
   - Install dependencies
   - Train or load YOLOv8 model
   - Upload a video or enable webcam
   - Run detection loop

3. Webcam Access (optional):  
   You can use JavaScript in Colab to access your webcam like this:

   ```python
   from IPython.display import display, Javascript
   display(Javascript('''navigator.mediaDevices.getUserMedia({ video: true })'''))
