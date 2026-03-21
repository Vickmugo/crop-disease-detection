# crop-disease-detection
Crop Disease Detection using CNN and MobileNetV2
#Crop Disease Detection Using Machine Learning
A Supervised Learning Approach with Convolutional Neural Networks
Group 13 — University of Eastern Africa, Baraton
Mugo Victor | Wisley Otieno | Kioko Joshua
Course: Artificial Intelligence (COSC440)
Instructor: Dr. Mony Victor Otieno
About
This project develops a supervised Machine Learning model that detects and classifies crop diseases from leaf images using a Convolutional Neural Network (CNN) with Transfer Learning based on the MobileNetV2 architecture. The model was trained on the PlantVillage Dataset containing 54,305 labeled images across 38 disease categories and 14 crop species.
Model Performance
The model achieved a best validation accuracy of 93.75%, surpassing the set target of 90%. Training was conducted on a T4 GPU in Google Colab over 5 epochs using TensorFlow and Keras.
Dataset
PlantVillage Dataset — 54,305 images, 38 classes, 14 crop species. Available on Kaggle at https://www.kaggle.com/datasets/abdallahalidev/plantvillage-dataset
Technologies Used
Python, TensorFlow, Keras, MobileNetV2, Google Colab, Scikit-learn, Matplotlib
How to Run
Open the Google Colab notebook, upload the PlantVillage dataset to Google Drive, and run all cells in order.
Colab: https://colab.research.google.com/drive/1Hdg5Orp5BwuEfcc84HgScPw7ombSTWjf?usp=sharing
