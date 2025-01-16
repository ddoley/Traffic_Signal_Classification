# Traffic_Signal_Classification
## 🚀 Project Description
This project is focused on classifying traffic signs using deep learning techniques, specifically a Convolutional Neural Network (CNN). The dataset used is the German Traffic Sign Recognition Benchmark (GTSRB), which contains images of various traffic signs categorized into different classes. The objective is to develop an efficient model that accurately predicts the type of traffic sign given an image.

## 📂Dataset:
https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign

## 🔑 Key Features

Image classification using CNN on the German Traffic Sign Recognition Benchmark dataset.

Preprocessing images by resizing, normalizing, and converting them into arrays.

One-hot encoding (OHE) of labels for effective model training.

Data augmentation and dropout layers to reduce overfitting.

Model evaluation using accuracy, loss, and validation accuracy plots.

Use of transfer learning for performance improvement.

Saving and loading trained models to avoid redundant retraining.

Testing the model on an independent test dataset using test.csv.

## 🛠 Tech Stack Used

Python (numpy, pandas, matplotlib, PIL, os, cv2, tensorflow, sklearn)

TensorFlow/Keras for building the CNN model

OpenCV (cv2) for image processing

Pandas and NumPy for data manipulation

Matplotlib for visualization

Scikit-learn for train-test split and data preprocessing

## 🔄 Workflow

- Data Collection: Images categorized into folders based on traffic sign classes.  
- Data Preprocessing: Images extracted, resized, converted to NumPy arrays, and stored with labels. 
- Data Splitting: Data divided into training and testing sets; labels one-hot encoded. 
- Model Building: A CNN model with Conv2D, MaxPooling2D, Dropout, Flatten, and Dense layers defined. 
- Model Compilation & Training: Model compiled using categorical cross-entropy loss, Adam optimizer, and accuracy metric; trained while monitoring accuracy and loss. 
- Model Evaluation & Testing: Predictions made on test data, accuracy computed. 
- Model Saving & Deployment: Trained model saved and loaded for real-world traffic sign predictions. 
- Final Predictions: The model accurately classifies traffic signs and maps them to human-readable names. 

## 📊 Results & Performance

Achieved high accuracy (~95%) on the test dataset.

Model generalizes well with minimal overfitting due to dropout layers and regularization.

Plots of training accuracy and validation accuracy indicate stable learning behavior.

## 📌 Suggestions & Improvements

Use a larger dataset: Incorporate additional real-world traffic signs for better generalization.

Hyperparameter tuning: Experiment with different architectures, batch sizes, and optimizers.

Increase training epochs: More epochs might improve classification accuracy.

Use Transfer Learning: Pretrained models like ResNet or VGG16 can further enhance performance.

Deploy the model: Create a real-time traffic sign detection system using OpenCV and integrate with Raspberry Pi for IoT applications.
