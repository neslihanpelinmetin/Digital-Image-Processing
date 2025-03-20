# Digital Image Processing – Assignment 1

**Course: CMPE 362 / CS 563 – TED University**
**Term: Spring 2023**
**Due Date: April 9th, 2023**

## Overview

This assignment focuses on image editing techniques, including foreground-background image composition and applying image processing effects such as smoothing and sharpening.

## Tasks

### **Part 1: Foreground-Background Image Composition**
- Select a **foreground image** from the **MSRA10K dataset** along with its binary mask.
- Choose a **background image** (any image is acceptable).
- Implement a function `combineForegroundBackground` to overlay the foreground image onto the background while preserving object integrity.

### **Part 2: Image Enhancement**
- Implement a **Gaussian smoothing function** for background blurring.
- Implement an **unsharp masking function** to sharpen the foreground.
- Combine the processed foreground and background to observe the effects.

## Implementation Requirements

- **Python** with **OpenCV** is used for image processing.
- Implement functions **manually** instead of relying on built-in library functions for merging images.
- Ensure correct handling of **image overflow** when combining images.

## Deliverables

- **part1.ipynb:** Implementation of `combineForegroundBackground` and results for Part 1.
- **part2.ipynb:** Implementation of `combineForegroundBackground`, `gaussianSmoothing`, and `unsharpMasking` along with results for Part 2.

- **Report containing:**
  - Explanation of the methodology
  - Results with different parameter settings
  - Discussion on how parameter variations impact the output

## Documentation
📄 **Assignment PDF:** [CMPE362_CS563_HW1.pdf](./Homework-1/CMPE362_CS563_HW1.pdf)  
📑 **Report:** [Neslihan_Pelin_Metin_CMPE_362_Hw1.pdf](./Homework-1/NeslihanPelinMetin_CMPE_362_Hw1.pdf)
