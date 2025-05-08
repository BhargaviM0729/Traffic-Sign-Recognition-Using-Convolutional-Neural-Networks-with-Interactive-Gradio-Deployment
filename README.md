# Traffic-Sign-Recognition-Using-Convolutional-Neural-Networks-with-Interactive-Gradio-Deployment
# Traffic Sign Recognition using CNN and Gradio

This project demonstrates a simple deep learning-based Traffic Sign Recognition system built with TensorFlow/Keras and deployed using Gradio. The model is capable of classifying various traffic signs (e.g., Stop, Keep Left) with high accuracy.

##  Project Highlights

- Built and trained a Convolutional Neural Network (CNN) for image classification of traffic signs.
-  Utilized a labeled dataset of traffic sign images for training and validation.
-  Integrated Gradio for an interactive web interface where users can upload a traffic sign image and get the predicted label.
-  Displays prediction confidence along with the label.

##  How It Works

1. Upload an image of a traffic sign via the Gradio interface.
2. The model processes the image and classifies it into one of the trained categories.
3. The predicted class label and confidence score are displayed.

## 📷 Sample Outputs

Below are screenshots of the application successfully predicting traffic signs:

### Example 1: Stop Sign
![Stop Sign Prediction](./outputs/Screenshot_63.png)

### Example 2: Keep Left
![Keep Left Prediction](./outputs/Screenshot_62.png)

> Both predictions returned a **100% confidence score**, demonstrating excellent model performance on these examples.

## Requirements

- Python 3.7+
- TensorFlow / Keras
- Gradio
- NumPy
- Matplotlib 



