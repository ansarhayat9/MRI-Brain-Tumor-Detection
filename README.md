# MRI Brain Tumor Detection Using Deep Learning

## Overview
This project is a web application that uses deep learning to detect and classify brain tumors from MRI images. Built as a student learning project, it demonstrates the application of AI and computer vision in healthcare. The app allows users to upload MRI scans and receive instant predictions about the presence and type of brain tumor.

## Features
- **AI-powered tumor detection** from MRI images
- **Classifies scans into four categories:**
  - Glioma
  - Meningioma
  - Pituitary
  - No Tumor
- **User-friendly web interface** for image upload and results
- **Instant predictions** with confidence scores
- **Secure and private:** Images are not stored after analysis

## Dataset
- The model is trained on the [Brain Tumor MRI Dataset (Kaggle)](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset)
- The dataset contains MRI images categorized into four classes: glioma, meningioma, pituitary, and no tumor.

## Model File Notice
> **Note:** The trained model file (`model.h5`) is too large to be uploaded to GitHub due to file size restrictions. To run this project, you must download or train the model separately and place it in the `models/` directory as `model.h5`.

## Setup Instructions
1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/brain-tumor-detection.git
   cd brain-tumor-detection
   ```
2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
3. **Download the trained model:**
   - If you have a trained model, place it in the `models/` directory as `model.h5`.
   - Or, train your own model using the provided dataset link and save it as `models/model.h5`.
4. **Run the application:**
   ```bash
   python main.py
   ```
5. **Open your browser and go to:**
   - `http://127.0.0.1:5000/` (or the address shown in your terminal)


## Project Structure
```
├── main.py
├── requirements.txt
├── models/
│   └── model.h5  # <--- Download or train and place here
├── templates/
│   └── index.html
├── uploads/
└── ...
```

## Acknowledgements
- Dataset: [Kaggle - Brain Tumor MRI Dataset](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset)
- Built as a student project for learning purposes.

## Disclaimer
This tool is for educational and research purposes only. It is **not** intended for clinical or diagnostic use. For medical advice, always consult a certified healthcare professional. 
