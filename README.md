# DreamView
E-commerce AR Visual Furniture Application using Machine Learning
## 🔍 Features
- AR-based surface detection with Google ARCore
- Real-time room dimension prediction using on-device ML
- Android app built with Sceneform + Java
- Synthetic training data generated in Python (1500 samples)
- TFLite model integrated for offline performance
- Firebase used for data storage and catalog management

## 📁 Project Structure
app/ → Android source code (Java, ARCore)

model/ → Trained .tflite file

notebooks/ → Jupyter Notebook for model training

screenshots/ → Sample outputs and AR predictions

## 📊 Model
- Framework: TensorFlow + Keras
- Output: Length, Width, Height (multi-output regression)
- Evaluation: MSE = 0.0142, R² = 0.967
