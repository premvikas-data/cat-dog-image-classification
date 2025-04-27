# Cat vs Dog Image Classification 🐱🐶

This project implements a machine learning pipeline to classify images of cats and dogs using multiple techniques: Principal Component Analysis (PCA) for dimensionality reduction, classical ML models (SVM, Random Forest), and a deep learning model (CNN).

## Project Highlights
- 📸 Image Preprocessing: Resizing, normalization, and flattening
- 🔎 Dimensionality Reduction: PCA to 50 components
- 🤖 Models Trained:
  - Support Vector Machine (SVM)
  - Random Forest Classifier
  - Convolutional Neural Network (CNN)
- 🎯 Hyperparameter Tuning:
  - Random Search CV for Random Forest
  - Keras Tuner for CNN
- 📈 Final Test Accuracy: CNN (~62%)

## Technologies Used
- Python (Pandas, Scikit-Learn, Keras, TensorFlow, Matplotlib)
- Jupyter Notebook
- PCA for feature reduction
- Keras Tuner for deep learning optimization

## Data
- 1000 images for training (cats and dogs)
- 100 images for testing
- Images resized to 350x350 pixels with 3 color channels (RGB)

## Future Work
- Explore deeper CNN architectures like ResNet, VGG
- Use GPUs for faster training and broader hyperparameter search
- Apply data augmentation for improved model generalization

## Author
Prem Vikas
