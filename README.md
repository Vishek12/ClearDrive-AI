
#  ClearDrive-AI

![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)
![OpenCV](https://img.shields.io/badge/OpenCV-Computer%20Vision-green.svg)
![Machine Learning](https://img.shields.io/badge/ML-Classification-orange.svg)
![Status](https://img.shields.io/badge/Status-Active%20Development-brightgreen.svg)
![License](https://img.shields.io/badge/License-MIT-lightgrey.svg)

---

##  Overview

**ClearDrive-AI** is a computer vision-based driver safety system that classifies driver sobriety state (**sober vs impaired**) using image data.

The project uses **OpenCV preprocessing**, feature extraction, and machine learning classification techniques to analyze visual cues and evaluate driver condition.

---

##  Objective

To explore how computer vision and machine learning can be applied to road safety by building a pipeline that detects impairment indicators from image-based inputs.

---

##  System Architecture

---

            ┌─────────────────────┐
            │   Input Images      │
            └────────┬────────────┘
                     ↓
        ┌───────────────────────────┐
        │  OpenCV Preprocessing     │
        │  - Resize                 │
        │  - Normalization          │
        │  - Noise Reduction        │
        └────────┬──────────────────┘
                     ↓
        ┌───────────────────────────┐
        │ Feature Extraction        │
        │ - Facial/visual cues      │
        │ - Pixel-based features    │
        └────────┬──────────────────┘
                     ↓
        ┌───────────────────────────┐
        │ ML Classification Model   │
        │ - Sober vs Impaired       │
        └────────┬──────────────────┘
                     ↓
        ┌───────────────────────────┐
        │ Evaluation & Metrics      │
        │ Accuracy / Error Analysis │
        └───────────────────────────┘


## Tech Stack

- Python  
- OpenCV   
- NumPy, Pandas   
- Scikit-learn / CNN Model   
- Jupyter Notebook
- Kaggle 

---

##  Methodology

**1. Data Preprocessing**
- Image resizing and normalization
- Noise reduction using OpenCV filters

**2. Feature Engineering**
- Extraction of relevant visual patterns
- Conversion into ML-ready feature vectors

**3. Model Training**
- Supervised binary classification
- Trained on labeled image dataset

**4. Evaluation**
- Accuracy measurement
- Residual and error analysis
- Generalization across test splits


## 📈 Results

- Built an end-to-end computer vision classification pipeline  
- Evaluated performance on unseen test data  
- Conducted residual analysis for model reliability  
- Demonstrated generalizable prediction behavior across splits  

---

##  Important Note

Large model files (`.h5`, `.keras`) are excluded due to GitHub size limits (>100MB).  
Models can be regenerated using the training notebooks included in this repository.

---

##  Future Improvements

- Real-time webcam inference system  
- Improved CNN architecture optimization  
- Flask + React deployment  
- Larger dataset for better generalization  
- Integration into driver monitoring systems  



---

## Key Takeaway

ClearDrive-AI demonstrates a full computer vision + machine learning pipeline applied to a real-world safety problem, from raw image processing to model evaluation and prediction.
**
