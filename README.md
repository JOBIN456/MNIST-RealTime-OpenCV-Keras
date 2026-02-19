# Live MNIST Digit Recognition with Webcam

Real-time handwritten digit recognition (0–9) using a **Convolutional Neural Network (CNN)** trained on the **MNIST** dataset, with live prediction from a webcam (or IP camera) using **OpenCV**.


## Features
- Classic MNIST CNN model (~99% test accuracy)
- Live video stream prediction
- Simple preprocessing (grayscale → resize → threshold → normalize)
- Shows predicted digit + confidence score on the frame
- Works with webcam or phone-as-webcam streams (e.g. IP Webcam app)



## Requirements

- Python 3.8+
- TensorFlow / Keras
- OpenCV
- NumPy

```bash
pip install -r requirements.txt
