# Handwritten-Digit-Recognition
This project is a deep learning-based digit recognition system that identifies handwritten digits (0–9) drawn by a user in a graphical interface. It uses a Convolutional Neural Network (CNN) trained on the MNIST dataset to perform image classification. The project also includes a Tkinter GUI that allows users to draw digits and receive real-time predictions.
🔧 Tech Stack
Programming Language: Python

Libraries Used:

TensorFlow / Keras – for model building and training

NumPy – for numerical operations

Pillow – for image processing

Tkinter – for GUI development

pywin32 – to grab screen content for digit capture (Windows only)

🏗️ Project Structure
train_digit_recognizer.py
Trains a CNN using the MNIST dataset. The model includes multiple convolutional and dense layers to learn image features. The final trained model is saved as mnist.h5.

gui_digit_recognizer.py
Provides a simple GUI where the user can:

Draw a digit on a canvas

Click “Recognise” to get the predicted digit and confidence

Click “Clear” to reset the canvas

🎯 Key Features
Real-time digit prediction using a trained CNN model

User-friendly drawing interface with Tkinter

Confidence score displayed along with the predicted digit

Easy to train and customize with different datasets or CNN architectures

📈 Applications
Educational tools for learning machine learning and computer vision

Prototype for digit input systems like postal code readers, cheque scanners, etc.

Foundation for advanced OCR (Optical Character Recognition) systems

🚀 Future Improvements
Support for mouse pressure or touchscreen inputs

Model enhancement using advanced techniques like data augmentation or transfer learning

Cross-platform support (ImageGrab alternative for Linux/macOS)

