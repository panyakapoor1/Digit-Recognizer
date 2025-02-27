# Digit Recognizer using Artificial Neural Network (ANN)

## 📌 Project Overview
This project is a **handwritten digit recognizer** built using an **Artificial Neural Network (ANN)**. It was developed as part of a **hands-on AI workshop**, where we implemented a simple model for digit classification.

## 📂 Dataset Used
We used the **MNIST dataset**, which consists of **60,000 training images** and **10,000 testing images** of handwritten digits (0-9). Each image is a **28x28 grayscale pixel representation** of a single digit.

## 🏗️ Model Architecture
- **Input Layer**: 784 neurons (28x28 pixels flattened)
- **Hidden Layers**: Fully connected layers with activation functions
- **Activation Function**: ReLU for hidden layers
- **Output Layer**: 10 neurons (one for each digit 0-9) with **Softmax activation**
- **Loss Function**: Categorical Cross-Entropy
- **Optimizer**: Adam or SGD

## 🔧 Implementation Steps
1. Load and preprocess the MNIST dataset
2. Normalize pixel values (0-255 scaled to 0-1)
3. Build the ANN model using a deep learning framework (TensorFlow/Keras)
4. Train the model with training data
5. Evaluate the model performance on test data
6. Make predictions on new handwritten digits

## 📊 Results & Accuracy
After training, the model achieved **high accuracy** on the test dataset, demonstrating its ability to recognize handwritten digits effectively.

## 🚀 Technologies Used
- Python
- TensorFlow/Keras
- NumPy & Pandas
- Matplotlib (for visualization)

## 🎯 Learning Outcomes
✅ Understanding how **Artificial Neural Networks** work  
✅ Practical experience in **digit classification**  
✅ Hands-on implementation of **AI/Deep Learning models**  
✅ Model evaluation & improvement techniques  

## 📌 Future Enhancements
- Improve accuracy by using **CNNs** (Convolutional Neural Networks)
- Experiment with **hyperparameter tuning**
- Deploy the model as a **web app using Flask/Streamlit**

## 📜 Acknowledgments
This project was developed as part of an **AI Workshop**, where we explored the fundamentals of deep learning and model implementation.
