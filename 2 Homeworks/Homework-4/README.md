# 🎯 Digital Image Processing – Assignment 4

📚 **Course:** CMPE 362 / CS 563 – TED University  
📅 **Term:** Spring 2023  
⏳ **Due Date:** June 11th, 2023  

## 🔍 Overview

This assignment focuses on **image stitching**, where multiple overlapping images are combined to create a **panorama** using **feature detection, matching, and geometric transformation techniques.**

## 🚀 Tasks

### Part 1: Feature Detection and Matching
1. Load image pairs from **input_set1.zip** and **input_set2.zip**.
2. Convert images to **grayscale** and detect **SIFT keypoints**.
3. Extract **128-dimensional feature descriptors** for each keypoint.
4. Perform **feature matching** using **BFMatcher** with **knnMatch** (k=2).
5. Apply the **ratio test** to filter out poor matches.
6. Visualize the **good matches** using `drawMatchesKnn`.

### Part 2: Image Registration
1. Estimate the **affine transformation matrix** using `estimateAffine2D`.
2. Apply **warpAffine** to align the second image to the first.
3. Create a **mask** to define valid transformed pixels.
4. Visualize the **transformed image and mask.**

### Part 3: Image Stitching
1. Extend the first image to match the dimensions of the transformed second image.
2. Create a mask for the first image to differentiate overlapping regions.
3. Blend the images by taking the **average** in overlapping regions.
4. Visualize the **final stitched image**.

## ⚙️ Implementation Requirements

- Use **Python** with **OpenCV** and **NumPy**.
- Implement all blending operations **manually**, without built-in stitching functions.
- Ensure smooth transition between stitched images.

## 📂 Deliverables

- **hw4_input1.ipynb:** Implementation and results for **image set 1**.
- **hw4_input2.ipynb:** Implementation and results for **image set 2**.
- **Report including:**
  - Explanation of the methodology
  - Results with different parameter settings
  - Discussion of how parameter variations impact the results

## 📄 Documentation

**Assignment PDF:** [CMPE362_CS563_HW4.pdf](./Homework-4/CMPE362_CS563_HW4.pdf)  
**Report Part 1:** [NpelinMetin_C362Hw4PaR-1.pdf](./Homework-4/NpelinMetin_C362Hw4PaR-1.pdf)  
**Report Part 2:** [NpelinMetin_C362Hw4PaR-2.pdf](./Homework-4/NpelinMetin_C362Hw4PaR-2.pdf)  
**Report Part 3:** [NpelinMetin_C362Hw4PaR-3.pdf](./Homework-4/NpelinMetin_C362Hw4PaR-3.pdf)  

