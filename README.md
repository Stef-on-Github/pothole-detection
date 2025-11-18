# 🛣️ Pothole Detection System  

A **Flask + Tkinter powered application** integrating **YOLOv8 deep learning models** for detecting potholes from images, videos, and live camera feeds. This project demonstrates advanced skills in **computer vision, deep learning, and full-stack integration**, with a focus on usability and real-world impact.

---

## 🚀 Features
- **Multi-Input Modes**  
  - 📷 Image detection  
  - 🎥 Video detection  
  - 📡 Real-time camera detection  

- **User-Friendly Interfaces**  
  - Flask routes for launching detection modes  
  - Tkinter GUIs for interactive file selection and visualization  

- **Smart Notifications**  
  - Visual bounding boxes with labels  
  - 🔊 Audio alerts using `pygame` when potholes are detected  

- **File Management**  
  - Save processed images and videos directly from the UI  
  - Organized dataset handling with sorted training/validation/test sets  

---

## 🧠 Skills Demonstrated
- **Deep Learning & Computer Vision**  
  - Training and deploying YOLOv8 models for object detection  
  - Handling large datasets with Git LFS for reproducibility  

- **Software Engineering Practices**  
  - Modular project structure with clear separation of concerns  
  - Integration of multiple frameworks (Flask, Tkinter, OpenCV, Pygame)  

- **Data Science Workflow**  
  - Dataset preprocessing and organization  
  - Model evaluation and threshold tuning  

- **Collaboration & Documentation**  
  - GitHub version control with large file support  
  - Clear, reproducible workflow for collaborators  

---

## 📂 Project Structure
Code/
├── .gitattributes
├── conversion_txt.py
├── dataset.zip
├── dataset_sorted.zip
├── google_colab_steps.ipynb
├── gpu.py
├── main_yolov8n_model.py
├── main_yolov8s_yolov8m_model.ipynb
├── yolo11n.pt
├── yolov8m.pt
├── yolov8n.pt
├── yolov8s.pt
├── yolov8_dataset.yaml
├── audio_output/
│   └── pothole_detected_voice.mp3
├── pothole_detection_app/
│   ├── app.py
│   ├── camera_input.py
│   ├── image_input.py
│   ├── video_input.py
│   └── templates/
│       ├── camera.html
│       ├── image.html
│       ├── index.html
│       └── video.html
└── runs/
    └── detect/
        ├── train/
        │   ├── args.yaml
        │   ├── confusion_matrix.png
        │   ├── PR_curve.png
        │   ├── results.csv
        │   ├── results.png
        │   ├── ...
        │   └── weights/
        │       ├── best.pt
        │       └── last.pt
        ├── train2/
        │   ├── args.yaml
        │   ├── confusion_matrix.png
        │   ├── PR_curve.png
        │   ├── results.csv
        │   ├── results.png
        │   ├── ...
        │   └── weights/
        │       ├── best.pt
        │       └── last.pt
        └── train3/
            ├── args.yaml
            ├── confusion_matrix.png
            ├── PR_curve.png
            ├── results.csv
            ├── results.png
            ├── ...
            └── weights/
                ├── best.pt
                └── last.pt


---

## 🛠️ Tech Stack
- **Languages:** Python  
- **Frameworks:** Flask, Tkinter  
- **Libraries:** OpenCV, Ultralytics YOLO, Pygame, PIL  
- **Tools:** Git, GitHub CLI, Git LFS  

---

## 🌟 Impact
This project showcases how **AI can be applied to real-world infrastructure problems**. By detecting potholes in roads, it contributes to:  
- Safer transportation  
- Preventive maintenance planning  
- Smart city initiatives  

---
