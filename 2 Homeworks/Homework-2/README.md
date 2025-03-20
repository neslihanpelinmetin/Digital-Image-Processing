# 🎯 Digital Image Processing – Assignment 2

📚 **Course:** CMPE 362 / CS 563 – TED University  
📅 **Term:** Spring 2023  
⏳ **Due Date:** April 30th, 2023  

## 🔍 Overview

This assignment focuses on **template matching** and **image filtering in the frequency domain** using **Butterworth filters**. You will implement different similarity measures for **template matching** and apply **low-pass and high-pass filters** in the frequency domain.

## 🚀 Tasks

### **Part 1: Template Matching**
1. Implement **four different template matching measures**:
    - Correlation
    - Zero-mean Correlation
    - Sum of Squared Differences (SSD)
    - Normalized Cross-Correlation (NCC)
2. Compare an input image with a given template using these measures and visualize the results.
3. Identify the **best-matching location** in the input image for each measure.
4. Discuss the effectiveness of each similarity measure.
 
### **Part 2: Image Filtering in the Frequency Domain**
1. Implement **Butterworth low-pass** and **high-pass** filters.
2. Apply the filters to the **Lenna** image using different parameters.
3. Analyze the effects of filter parameters **D₀** (cutoff frequency) and **n** (order).
4. Discuss the **ringing artifacts** and filter effectiveness in both frequency and spatial domains.

## ⚙️ Implementation Requirements

- Use **Python** with **OpenCV** and **NumPy**.
- Implement all functions manually without using built-in template matching functions.
- Shift frequency domain representations to the center before visualization.

## 📂 Deliverables

- **part1a.ipynb:** Implementation of template matching for input1.
- **part1b.ipynb:** Implementation of template matching for input2.
- **part2a.ipynb:** Butterworth low-pass filtering.
- **part2b.ipynb:** Butterworth high-pass filtering.
- **Report** including:
  - Explanation of the methodology
  - Results with different parameter settings
  - Discussion of how parameter variations impact the results
 
## 📄 Documentation
**Assignment PDF:** [CMPE362_CS563_HW2.pdf](./Homework-2/CMPE362_CS563_HW2.pdf)  
**Report:** [Npelin_Metin_CMPE_362_Hw2.pdf](./Homework-2/Npelin_Metin_CMPE_362_Hw2.pdf)
