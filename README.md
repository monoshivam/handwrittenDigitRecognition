# handwrittenDigitRecognition

<img width="587" height="360" alt="image" src="https://github.com/user-attachments/assets/39192937-3ad2-44bb-bc24-223c2134c900" />


This project implements a **Handwritten Digit Recognition** system using a Convolutional Neural Network (CNN). It includes a Graphical User Interface (GUI) where users can draw digits on a canvas, and the model predicts the digit in real-time.

## 📌 Features
- **Deep Learning Model:** Uses a CNN trained on the MNIST dataset (60,000 training images).
- **High Accuracy:** Achieves ~97% accuracy on test data.
- **Interactive GUI:** Built with `tkinter`, allowing users to draw digits via mouse input.
- **Real-time Prediction:** Instantly classifies the drawn digit.

## 🛠️ Tech Stack
- **Language:** Python
- **Deep Learning:** TensorFlow, Keras
- **GUI:** Tkinter
- **Image Processing:** Pillow (PIL), NumPy

## 📂 Project Structure
- `main_digit_recognizer.py` (or similar): Script to build, train, and save the CNN model.
- `gui_tkinter.py`: The main application script that launches the drawing interface.
- `mnist.h5`: The pre-trained model file (generated after running the training script).

## 🚀 Installation & Setup

```bash
git clone [https://github.com/monoshivam/handwrittenDigitRecognition.git](https://github.com/monoshivam/handwrittenDigitRecognition.git)
cd handwrittenDigitRecognition
pip install numpy tensorflow keras pillow
pip install pywin32
python gui_digit_recognizer.py
