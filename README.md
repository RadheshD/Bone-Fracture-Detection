# Bone Fracture Detection and Classification

## Abstract
This project presents a system for bone fracture detection and classification in X-ray images using machine learning. The system feeds X-ray images into a neural network model trained on a sizable dataset corresponding to various sorts of fractures. Python is used to create a software system that can import an image and supply insights about the fracture. The project contrasts Convolutional Neural Networks (CNN) and MobileNet models, and incorporates a hybrid model combining MobileNet with Random Forest.

## Introduction
Bone fractures are a prevalent medical condition often requiring precise and timely diagnosis. Conventional manual examination of X-ray images by radiologists can be prone to errors and is time-consuming. This project bridges the gap by developing a reliable and robust software solution integrating deep learning to automate fracture diagnosis, enhancing diagnostic accuracy and reducing the burden on healthcare professionals.

## Features
- **Image Upload and Preprocessing:** Upload X-ray images for analysis; automatic preprocessing (resizing, normalization).
- **Fracture Detection & Classification:** Detect the presence of fractures and classify them using CNN and MobileNet models.
- **Hybrid Model Approach:** Utilizes a hybrid model combining MobileNet (for feature extraction) and Random Forest (for classification) to improve accuracy and efficiency.
- **Result Display:** Displays detected fractures, classification, and confidence scores, providing actionable insights.
- **Report Generation:** Generates a comprehensive report summarizing results and confidence levels.
- **Comparison of Models:** Provides a comparison of results between CNN, MobileNet, and the Hybrid model.

## Technology Stack
- **Languages:** Python, HTML, CSS
- **Frontend:** HTML, CSS, Bootstrap
- **Backend/Frameworks:** Python, Django (assumed based on project structure)
- **Machine Learning:** TensorFlow/Keras (CNN, MobileNet), Scikit-Learn (Random Forest)
- **Database:** SQLite / SQLYog (Xampp)

## Project Structure
- `BACKEND/`: Contains the machine learning models, Jupyter Notebooks for training, and related scripts (e.g., `cnn.h5`, `mobilenet.h5`, `random_forest_classifier.pkl`).
- `FRONTEND/`: Contains the web application (Django) including user interface for uploading X-ray images and displaying results.

## Setup and Installation
1. Clone the repository.
2. Install dependencies (e.g., `pip install -r requirements.txt` located in `FRONTEND/`).
3. Ensure the pre-trained model files (`.h5`, `.pkl`, `.pt`) are placed in the `BACKEND/Bone Break Classification/` directory (these large model files are excluded from Git).
4. Run the application server (e.g., `python manage.py runserver` from the `FRONTEND/` directory).
