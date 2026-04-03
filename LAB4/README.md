# Object Detection Lab Assignment

##  Student Details

* **Name:** Jay
* **Student ID:** 202511068

---

##  Assignment Title

Implementation and Analysis of Object Detection Techniques:
IoU, R-CNN, Fast R-CNN, Faster R-CNN, NMS, and YOLO

---

##  Project Overview

This project demonstrates the working of multiple object detection techniques from traditional methods (R-CNN) to modern deep learning approaches (YOLO).

The implementation includes:

* IoU (Intersection over Union) demonstration
* Manual R-CNN crop generation
* Fast R-CNN RoI Pooling
* Faster R-CNN inference
* Non-Maximum Suppression (NMS)
* YOLO training pipeline

---

##  Tasks Covered

###  Task 1: IoU Demonstration

* Implemented IoU calculation between bounding boxes
* Visualized overlapping regions

---

###  Task 2: Manual R-CNN Crop Loop

* Generated region proposals
* Cropped image regions manually
* Passed crops to classifier

---

###  Task 3: Fast R-CNN (RoI Pooling)

* Implemented RoI Pooling
* Extracted fixed-size feature maps
* ⏱ Execution time printed in notebook output

---

###  Task 4: Faster R-CNN Inference

* Used pre-trained Faster R-CNN model
* Performed object detection on sample images
* ⏱ Execution time printed in notebook output

---

###  Task 5: Non-Maximum Suppression (NMS)

* Implemented NMS algorithm manually
* Removed overlapping bounding boxes

---

###  Task 6: YOLO Training

* Trained YOLO model on dataset
* Evaluated detection performance

---

##  Execution Instructions

### 1. Clone Repository

```bash
git clone https://github.com/your-username/Object-Detection-Lab.git
cd Object-Detection-Lab
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Run Notebook

```bash
jupyter notebook notebooks/IT549_Lab4_Object_Detection.ipynb
```

---

##  Requirements

* Python 3.8+
* PyTorch
* OpenCV
* NumPy
* Matplotlib

---

##  Notes

* Execution times for Task 3 and Task 4 are printed in outputs.
* Conceptual answers are included inside the notebook in Markdown cells.
* Code is modularized inside the `src/` directory.

---

##  Author

Jay
