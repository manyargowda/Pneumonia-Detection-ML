# Pneumonia-Detection-ML
Pneumonia detection system using CNN and Flask deployment
# Pneumonia Detection using Convolutional Neural Network

## Project Overview

This project is a deep learning-based web application that detects Pneumonia from chest X-ray images using a Convolutional Neural Network (CNN). The trained model is integrated with a Flask web application to allow users to upload X-ray images and receive predictions.

## Objective

To build and deploy a machine learning model capable of classifying chest X-ray images into:
- Normal
- Pneumonia

## Technologies Used

- Python
- TensorFlow / Keras
- Convolutional Neural Network (CNN)
- Flask
- NumPy
- OpenCV
- HTML and CSS

## Project Structure

```
Pneumonia-Detection-ML
│── app.py
│── train_model.py
│── templates/
│── README.md
```

## How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/manyargowda/Pneumonia-Detection-ML.git
cd Pneumonia-Detection-ML
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the Application

```bash
python app.py
```

Open your browser and go to:
http://127.0.0.1:5000/

## Model Information

- Model Type: Convolutional Neural Network
- Input: Chest X-ray images
- Output: Binary classification (Normal or Pneumonia)

## Features

- Image upload functionality
- Real-time prediction
- Web-based user interface
- Deep learning-based classification system

## Future Improvements

- Improve model performance and accuracy
- Deploy application on a cloud platform
- Add report generation feature

