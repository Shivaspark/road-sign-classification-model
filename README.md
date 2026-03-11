# Road Sign Recognition System with PyQt5 (Project #12)

The twelfth project in my **AI/ML Learning Path**. This project focuses on **Traffic Sign Classification**, a vital component for Autonomous Vehicles, integrated into a desktop application using **PyQt5**.

## 📌 Overview
This project implements a Deep Learning model (CNN) capable of identifying various traffic signs from images. The application provides a graphical user interface (GUI) where users can load images and receive immediate predictions with high confidence scores.

## 🛠️ Tech Stack
* **Language:** Python
* **Deep Learning:** TensorFlow / Keras
* **GUI Framework:** PyQt5
* **Image Processing:** OpenCV, PIL
* **Libraries:** NumPy, Matplotlib

## 🏗️ Project Architecture
1. **The Model:** A CNN architecture optimized for color image classification (typically 32x32 or 64x64 pixels).
2. **The Dataset:** Trained on the German Traffic Sign Recognition Benchmark (GTSRB) or similar datasets.
3. **The Interface:** A PyQt5-based application featuring:
    - **Image Loader:** To browse and select traffic sign images from the local system.
    - **Result Panel:** Displays the predicted class name and the probability.
    - **Preview Window:** Shows the processed image being analyzed by the model.

## ⚙️ How It Works
1. **Preprocessing:** Images are resized, normalized, and converted to the required input shape for the CNN.
2. **Classification:** The model processes the image through convolutional and pooling layers to determine the traffic sign category.
3. **GUI Logic:** PyQt5 handles the event-driven interactions, passing the image path to the prediction script and updating the UI with the result.

## 🚀 Quick Start
1. **Install Dependencies:**
   ```bash
   pip install tensorflow pyqt5 opencv-python pillow
2. **Give the data:**
   
   Create the folder `Dataset/train` , `Dataset/test` and give the data.

4. **Run the application**
   ```bash
   python main.py


*Progress: Successfully built a vision-based tool for intelligent transportation systems.*
