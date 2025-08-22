# Car Detection Project 🚗

This project is about detecting cars in real-time using **OpenCV** and **Deep Learning (YOLO)**.  
I created it as a simple computer vision project to practice object detection and to learn how to work with YOLO models in Python.  

---

## 📌 Features  
- Detects cars in images or from a webcam in real-time.  
- Uses **YOLO (You Only Look Once)** for object detection.  
- Draws bounding boxes around detected cars.  
- Simple to run and extend for detecting other objects as well.  

---

## ⚙️ Requirements  
Make sure you have the following installed:  

- Python 3.8+  
- OpenCV  
- Numpy  
- imutils (optional for easier video processing)  

You can install the dependencies with:  

```bash
pip install opencv-python numpy imutils
```

---

## ▶️ How to Run  
1. Clone this repository or download the notebook.  
2. Download YOLO weights and config files (YOLOv3 or YOLOv4).  
   - For example, you need:  
     - `yolov3.weights`  
     - `yolov3.cfg`  
     - `coco.names`  
3. Place these files in your project folder.  
4. Open the notebook `car-detection.ipynb`.  
5. Run the cells step by step.  

If you want to use webcam detection, make sure your camera works and update the webcam index if needed:  

```python
cap = cv2.VideoCapture(0)  # 0 is the default webcam
```

Press **'q'** to quit the webcam window.  

---

## 📊 Results  
- Cars are detected with bounding boxes in real-time.  
- You can also test it with static images or recorded videos.  
- The model can be extended to detect multiple objects (like people, traffic lights, etc.) since YOLO is trained on COCO dataset.  

---

## 🚀 Future Improvements  
- Integrate tracking to follow cars across frames.  
- Use a lighter model (like YOLOv5 or YOLOv8) for faster performance.  
- Deploy it as a small app with a simple UI.  

---

## 📖 Notes  
This project is mainly for **learning purposes**. It helped me practice:  
- Working with OpenCV  
- Using pre-trained YOLO models  
- Real-time detection with Python  
