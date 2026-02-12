# Convolutional Neural Networks & Computer Vision with TensorFlow

This project demonstrates an end-to-end implementation of a Convolutional Neural Network (CNN) for image classification using TensorFlow.  
The model architecture is inspired by a simplified Tiny VGG-style network.

---

## 📌 What This Project Covers

- Getting and loading image data
- Inspecting and exploring the dataset
- Visualizing sample images
- Understanding CNN architecture
- Building a Tiny VGG-style CNN model
- Binary image classification
- Data preprocessing and normalization
- Model training and evaluation
- Hyperparameter tuning
- Data augmentation to reduce overfitting
- Making predictions with a trained model
- Saving and loading trained models

---

## 🧠 CNN Architecture Overview

The model follows a typical CNN pipeline:

- Convolutional Layers
- ReLU Activation
- Max Pooling
- Fully Connected (Dense) Layers
- Output Layer (Sigmoid for Binary Classification)

Loss Function: `binary_crossentropy`  
Optimizer: `Adam`  
Evaluation Metric: `Accuracy`

---

## 🔄 Workflow

1. Import and prepare the data  
2. Preprocess the images (rescaling, batching, etc.)  
3. Build a baseline CNN model  
4. Train the model  
5. Evaluate performance  
6. Tune hyperparameters  
7. Apply data augmentation  
8. Make predictions  
9. Save and reload the trained model  

---

## 📊 Techniques Used

- TensorFlow & Keras API
- ImageDataGenerator / Data augmentation
- Model checkpointing
- Performance evaluation (accuracy & loss curves)

---

## 🚀 Future Improvements

- Add multiclass image classification
- Implement transfer learning (e.g., ResNet, EfficientNet)
- Deploy model using Streamlit

---

This project is part of my Deep Learning learning journey using TensorFlow.
