# Introduction to Convolutional Neural Networks (CNN)

## 📌 Overview

This notebook introduces Convolutional Neural Networks (CNNs) and their application in image classification. It covers data preprocessing, model creation, training, evaluation, and visualization of results.

## 📂 Project Structure

- **notebook/** → Jupyter Notebook.
- **data/** → .rar files of carrot and cucumber images found on the web (used Imageye chrome extension).

## 🏗️ Project Workflow

- **Data Handling**: Importing and preprocessing image datasets (oversampled using rotations).
- **Model Implementation**: Constructing a CNN with TensorFlow/Keras.
- **Training & Evaluation**: Training the model and assessing its performance.
- **Visualization**: Plotting accuracy, loss, and predictions.

## 🛠️ Technologies & Libraries Used

- TensorFlow/Keras
- OpenCV
- NumPy
- Matplotlib

## ⚙️ Installation & Usage

1. Install dependencies:
   ```bash
   pip install tensorflow opencv-python matplotlib numpy
   ```
2. Run the notebook step by step to train and evaluate a CNN model on an image dataset.

## 🎯 Key Takeaways

- Explores the use of CNNs in image classification tasks.
- Provides hands-on implementation of a deep learning model.
- Includes visualization of model performance and predictions.

---
### 📢 Conclusion
The CNN was trained on a web images, which was preprocessed and divided into training, validation, and test sets. The architecture consists of multiple convolutional and pooling layers, followed by dense layers for classification. After training for 2 epochs, the model was evaluated on the test set, achieving a **precision of 0.98**, a **recall of 0.99**, and a **binary accuracy of 0.99**. These results confirm the model's ability to effectively learn and distinguish image features.
