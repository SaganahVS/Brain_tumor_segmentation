🧠 Brain Tumor Classification System
This project implements a Brain Tumor Classification System using Convolutional Neural Networks (CNNs) to detect tumor types from MRI images. It uses a custom-trained model and offers an interactive Gradio UI for image-based predictions.

🔍 Features
Classifies MRI scans into: glioma, meningioma, notumor, pituitary
Uses TensorFlow/Keras for building and training a CNN
Handles image preprocessing with OpenCV
LabelBinarizer for multi-class output
Gradio interface for easy drag-and-drop predictions
🧠 How It Works
Load and preprocess brain MRI images (resized to 128x128).
Train a CNN model using Conv2D, MaxPooling, and Dropout layers.
Use the trained model to classify new images uploaded via the Gradio interface.
Display prediction results with confidence scores.
📁 Requirements
Python 3.x
Libraries:
tensorflow
opencv-python
numpy
scikit-learn
gradio
google.colab (for Drive access)
🚀 Usage
Run the script in Google Colab or locally with the dataset stored in:
