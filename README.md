
Age Prediction with CV: Built a CNN to predict age from face images for a retail use case (Khleb-Sol supermarket). Completed EDA, preprocessing, model training, and evaluation to support product targeting and age verification at checkout.

🧠 A computer vision project for predicting a person’s age from a photo using deep learning.

📌 Project Description
This project was completed as part of the Yandex Practicum Data Science course.
A supermarket chain, Khleb-Sol, plans to use a computer vision system to estimate customer age at checkout. The system will:

Analyze customer demographics and personalize product offerings

Monitor alcohol sales to minors

The goal was to build a neural network model that predicts approximate age from face images.

🧪 Technologies and Tools
Python

TensorFlow / Keras

OpenCV

Pandas, NumPy

Matplotlib, Seaborn

Jupyter Notebook

📊 Model Overview
Input: real-world face images with labeled ages

Preprocessing: image resizing, normalization, and augmentation

Model: CNN built with Keras

Evaluation: MAE (Mean Absolute Error) as a quality metric

🔍 Key Steps
Exploratory data analysis

Data preprocessing and augmentation

CNN model training

Performance evaluation

📈 Results 
The model used was ResNet50 with the Adam optimizer (learning rate = 0.0001). It was trained for 10 epochs.  
Achieved MAE = 5.9556, meaning the model’s predictions deviate by approximately ±6 years.

