# Transfer Learning for Image Classification using TensorFlow

This project demonstrates how to use **Transfer Learning (Feature Extraction)** to improve the performance of image classification models using TensorFlow and TensorFlow Hub.

---

## 📌 What is Transfer Learning?

Transfer learning is a technique where a pre-trained model is reused as the starting point for a new task. Instead of training a model from scratch, we leverage knowledge learned from large datasets like ImageNet.

---

## 📚 Topics Covered

- Transfer Learning with TensorFlow (Feature Extraction)
- Downloading and exploring the dataset
- Creating data loaders using `ImageDataGenerator`
- Setting up callbacks:
  - EarlyStopping
  - ModelCheckpoint
  - TensorBoard
- Creating models using TensorFlow Hub
- Comparing models using TensorBoard


---

## 🛠️ Technologies Used

- Python
- TensorFlow
- TensorFlow Hub
- TensorBoard
- NumPy
- Matplotlib

---

## 🧠 Workflow

1. Download and inspect the dataset
2. Prepare data loaders
3. Load a pre-trained model from TensorFlow Hub
4. Freeze base layers (Feature Extraction)
5. Add custom classification head
6. Compile and train the model
7. Monitor training using TensorBoard
8. Evaluate and compare results

---

## 📊 Model Comparison

Model performance was monitored and compared using TensorBoard for:
- Training accuracy
- Validation accuracy
- Loss curves

---

## 📌 Key Learning Outcomes

- Understanding feature extraction
- Using pre-trained models
- Implementing callbacks
- Monitoring experiments using TensorBoard
- Improving performance with transfer learning
