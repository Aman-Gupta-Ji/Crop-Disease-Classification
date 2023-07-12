# Crop Disease Classification

This repository contains the implementation of a smart agriculture system for crop disease classification. The system utilizes various technologies discussed in the previous section to accurately predict the condition of crops and help farmers take necessary measures to protect their crops. The system leverages various technologies such as IoT, machine learning, image processing, cloud computing, and Android development to monitor and improve the quality of potato crops.


## Project Stages

The project involved the following stages:

1. **Data Preprocessing:** All the photos in the dataset are downsized to a specific format as the first step of data preprocessing.
2. **Data Splitting:** The dataset is split into two groups, with 20% of the data allocated for testing and 80% for training.
3. **Data Augmentation:** To prevent overfitting, the training set is subjected to augmentation techniques such as rotation, resizing, and adding random noise to the photos.
4. **Feature Extraction:** This step involves employing convolutional operations and the initial layers of the CNN architecture to extract features from the images.
5. **Model Training:** The model is trained using the extracted features from the training set once the architecture has been constructed.
6. **Model Evaluation:** The accuracy of the model is evaluated using the test set.
7. **Web Application Development:** ReactJS is used to create the front-end web application, while FastAPI is utilized as the back-end server. The functionality of the application is tested using Postman.
8. **Model Deployment:** The trained model is saved to Google Cloud and a Google Cloud Function is created.
9. **Android Application Development:** An Android application is developed using React Native to allow users to submit photographs to the server and display the results.
10. **Image Processing and Feature Extraction:** Images captured by cameras set up on potato plants are processed to remove noise, and a trained model is used to extract features from the images.
11. **Results Presentation:** The results are returned to the application and displayed on a smartphone.

## Implementation Steps

The main steps involved in the implementation are as follows:

**A. Image Acquisition:** Cameras are set up on five potato plants to capture their images at regular intervals using Arduino. The images are stored in the cloud, resulting in a dataset of approximately 12,000 - 15,000 images over three months. Some images are also obtained from the Kaggle website to augment the dataset.

**B. Image Processing:** The captured images are processed using image processing techniques to clean them and remove noise. Around 5,000 to 6,000 images are selected from the dataset for further analysis.

**C. Model Development:** A Convolutional Neural Network (CNN) model is developed using deep learning techniques. The dataset is trained using the CNN algorithm, and the model is implemented using Python.

**D. Web Application Development:** A web application is developed using the ReactJS framework. The application utilizes the API developed in the previous stage to make predictions. The API is hosted on a server, and the web application calls this API to retrieve and present the results to the users.

The implementation of the smart agriculture system is designed to be user-friendly and easy to use. The accuracy of the model is validated by comparing the obtained results with the actual results. The system has shown high accuracy and reliability in its predictions. The web application has also been thoroughly tested to ensure smooth and efficient functionality.

## Authors

- Aman Gupta
- Muskan Janweja
- Kiran
- Sona Verma
- Dr. Vrince Vimal

## Abstract

This smart agriculture system that utilizes IoT, machine learning, image processing, cloud computing, and Android development to monitor and improve the quality of potato crops. The system captures real-time images of potato leaves using an IoT camera and Arduino module. These images are then processed using deep learning algorithms and image processing techniques to predict crop conditions. The results are communicated to farmers through an Android application, providing suggestions to prevent crop damage or loss. The system also includes a web application using React.js and FastAPI to predict plant diseases. The proposed system aims to reduce farm labor, increase efficiency, and improve the quality of crops.

## Index Terms

CNN, FastAPI, IoT, TensorFlow, React Js


## Introduction

Smart agriculture system combines technology and traditional farming practices to improve production and make farming easier for farmers. This project utilizes IoT, machine learning, image processing, cloud computing, and Android development to enhance crop quality and prevent crop destruction. By collecting data on crop conditions through IoT, processing real images of crops, training a dataset using deep learning, and providing updates and suggestions through an Android application, this project aims to reduce farm labor and increase efficiency.

## Methodology

The methodology for this project involves the use of IoT, machine learning, image processing, cloud computing, and Android development. Data collection involves capturing leaf images of crops and storing them in a cloud database. Image processing techniques are applied to select a subset of images from the dataset. Deep learning algorithms, specifically Convolutional Neural Networks (CNNs), are used to process the data and make predictions on crop conditions. An API is developed to predict crop diseases based on the CNN model. Additionally, a web application using React.js is created to call the API and predict diseases. The entire implementation is focused on improving crop quality and providing suggestions for preventive measures.

## Implementation

The implementation of the smart agriculture system involved several stages, including data preprocessing, data splitting, data augmentation, feature extraction, model training, model evaluation, web application development, model deployment, and Android application development. Real images of crops were captured using cameras set up on potato plants and stored in the cloud. Image processing techniques were applied to select a subset of images from the dataset. The dataset was then used to train a CNN model for crop disease classification. A web application using React.js and FastAPI was developed to predict diseases, and an Android application was created to submit photographs and display results. The results were presented on smartphones, providing accurate predictions for crop diseases.

## Conclusion

In conclusion, the smart agriculture system presented in this repository utilizes IoT, machine learning, image processing, cloud computing, and Android development to monitor and improve the quality of potato crops. The system captures real-time images, processes them using deep learning algorithms and image processing techniques, and provides accurate predictions for crop diseases. The web and Android applications enable farmers to receive suggestions for preventive measures and improve the efficiency of their farming practices. This implementation has the potential to reduce farm labor, increase crop quality, and address the challenges faced by traditional farming methods.
The implementation of the smart agriculture system has been successful, providing highly accurate predictions for crop disease classification. Farmers can utilize this system to predict the condition of their crops and take necessary measures to protect them from damage. Additionally, consumers can benefit by ensuring they receive high-quality food with the right nutrients for healthy living.


