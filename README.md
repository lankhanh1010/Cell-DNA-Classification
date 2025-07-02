# Bacteria Classification with Neural Networks  
**Binary Classification on Microscopy Data**

## Project Overview  
This project focuses on identifying bacteria of interest using a neural network-based classification model. Using microscopy data from **Prof. Chih Lai, University of St. Thomas**, we aim to distinguish between bacteria that warrant further biological investigation and those that do not.

## Dataset  
**File**: `CellDNA.csv`  
The dataset contains various measurements (e.g., size, center, texture) of thousands of bacteria observed under a microscope.

- The **last column** is the target variable:
  - `Non-zero`: Interesting bacteria
  - `0`: Not interesting

To simplify the problem, we transformed it into a **binary classification task**:
- `1` = Interesting bacteria  
- `0` = Not interesting bacteria

## Objectives  
- Design a neural network to classify bacteria based on provided features.
- Evaluate and interpret the model's performance using accuracy, loss, and confusion matrix.

## 📁 Acknowledgment  
Dataset provided by **Prof. Chih Lai** of the **University of St. Thomas**.
