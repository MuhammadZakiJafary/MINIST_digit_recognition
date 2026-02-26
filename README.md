📌 Project Overview

This project implements a handwritten digit recognition system using the MNIST dataset. A Convolutional Neural Network (CNN) is built and trained to classify images of digits from 0 to 9 with high accuracy.
The goal of this project is to understand image preprocessing, deep learning model building, training, and evaluation.

📂 Dataset
The MNIST dataset contains:
60,000 training images
10,000 testing images
Grayscale images (28x28 pixels)
10 classes (digits 0–9)

⚙️ Project Workflow
1️⃣ Data Preprocessing
Reshaped images to (28, 28, 1)
Normalized pixel values (0–255 → 0–1)
Encoded labels for classification

2️⃣ Model Architecture
Convolutional Layers
MaxPooling Layers
Fully Connected (Dense) Layers
Softmax output layer (10 classes)

3️⃣ Training
Model compiled using appropriate optimizer and loss function
Trained on training dataset
Validated using test dataset

4️⃣ Evaluation
Achieved ~99% accuracy on test data
Evaluated performance using model evaluation metrics

🚀 Features
✔️ Beginner-friendly deep learning project
✔️ Image classification using CNN
✔️ High model accuracy
✔️ Custom image prediction support

🛠️ Technologies Used
Python
TensorFlow / Keras
NumPy
Matplotlib
OpenCV

▶️ How to Run
Clone the repository
Open the notebook in Jupyter or Google Colab
Run all cells to train the model
Test with custom digit images

📈 Future Improvements
Add webcam-based digit recognition
Build GUI using Streamlit or Tkinter
Deploy as a web application

👨‍💻 Author
Muhammad Zaki
BS Software Engineering
Aspiring AI & Data Science Professional
