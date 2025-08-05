# YOLO-Object-Detection

A simple object detection project using YOLO and OpenCV. This project performs real-time object detection using pre-trained YOLOv3 or YOLOv4 models.

## 📄 File
- `yolo-od.ipynb`: The Jupyter Notebook with all the code for loading the YOLO model, running inference, and visualizing the results.

## 🛠️ Requirements
- OpenCV
- NumPy
- Pre-trained YOLO weights and config files

## 🚀 How to Use

1. Download the YOLO weights and config files (e.g. from [YOLO website](https://pjreddie.com/darknet/yolo/))
2. Make sure paths inside the notebook are correct.
3. Run all cells and test detection on images or video.

## 🧠 Example Use Cases
- Detecting people, cars, animals, etc. in real-time
- Applying object detection to video feeds

## 📸 Example Use

Run the notebook, and edit the path in this line:

img = cv2.imread("your-image.jpg")


##  Classes (COCO Dataset)

The model can detect 80+ objects like:

person, car, dog, bicycle, traffic light, etc.


---

Created by : Ahmed Al-Mutaz Bellah
