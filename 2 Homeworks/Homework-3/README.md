# 🎯 Digital Image Processing – Assignment 3

📚 **Course:** CMPE 362 / CS 563 – TED University  
📅 **Term:** Spring 2023  
⏳ **Due Date:** May 24th, 2023  

## 🔍 Overview

This assignment focuses on **plant image segmentation**, **leaf detection**, and **removal of invalid detections** using techniques such as **k-means clustering**, **distance transform**, and **Hough Transform**.

## 🚀 Tasks

### **Part 1: Plant Segmentation Using K-Means Clustering**
1. Select **two images** from the **Plant Phenotyping Dataset** (Ara2012 RGB images).
2. Apply **k-means clustering** to segment the plant from the background.
3. Try different **k values** and analyze their impact on segmentation results.
4. Generate a **binary mask** of the segmented plant.

### **Part 2: Leaf Detection Using Hough Transform**
1. Compute the **distance transform** of the binary mask.
2. Determine **minRadius** and **maxRadius** parameters based on the distance transform.
3. Convert the **RGB image** to **Lab color space** and apply **median filtering** to the _a channel_.
4. Detect leaves using **HoughCircles** with three different parameter settings.
5. Visualize and compare the detection results.

### Part 3: Elimination of Invalid Detections
1. Remove circles whose centers are **outside the plant mask.**
2. Display the filtered results and compare them with the original detections.

## ⚙️ Implementation Requirements

- Use Python with **OpenCV** and **NumPy**.
- Experiment with different **k values** for segmentation.
- Tune **Hough Transform parameters** to achieve optimal leaf detection.

## 📂 Deliverables

- **hw3_input1.ipynb:** Implementation and results for image 1.
- **hw3_input2.ipynb:** Implementation and results for image 2.
- **Report** including:
  - Explanation of the methodology
  - Results with different parameter settings
  - Discussion of how parameter variations impact the results

## 📄 Documentation

**Assignment PDF:** [CMPE362_CS563_HW3.pdf](./Homework-3/CMPE362_CS563_HW3.pdf)  
**Report:** [NpelinMetin_CMPE_362_Hw3R.pdf](./Homework-3/NpelinMetin_CMPE_362_Hw3R.pdf)  

🌿 Dataset available at [Plant Phenotyping Dataset](https://www.plant-phenotyping.org/datasets-home).
