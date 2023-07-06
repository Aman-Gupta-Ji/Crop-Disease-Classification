# Crop Disease Classification

This repository contains the implementation of a smart agriculture system for crop disease classification. The system utilizes various technologies discussed in the previous section to accurately predict the condition of crops and help farmers take necessary measures to protect their crops.

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

## Conclusion

In conclusion, the implementation of the smart agriculture system has been successful, providing highly accurate predictions for crop disease classification. Farmers can utilize this system to predict the condition of their crops and take necessary measures to protect them from damage. Additionally, consumers can benefit by ensuring they receive high-quality food with the right nutrients for healthy living.
