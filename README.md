
# Celebrity Image Classifier

The Celebrity Image Classifier is a machine learning project designed to classify images of celebrities using facial recognition and machine learning techniques. This project leverages various computer vision libraries like OpenCV for face and eye detection, wavelet transform for image preprocessing, and machine learning models for classification. The model is trained to recognize images of specific celebrities, and the project is deployed as a web application using Flask, with a front-end built using HTML, CSS, and JavaScript.




## Features

Face and Eye Detection: Utilizes Haar Cascades from OpenCV to detect faces and eyes in images.\
Wavelet Transform: Implements wavelet transforms to enhance image features and improve classification accuracy.\
Image Classification: Uses multiple machine learning algorithms (SVM, Random Forest, Logistic Regression) to classify images of celebrities, with Logistic Regression yielding the best results.
Model Persistence: The best-performing model is saved using joblib for future use and deployment.\
Flask Web App: A Flask-based web application serves the model, allowing users to upload images and receive predictions.\
Front-End: The front-end is built using HTML, CSS, and JavaScript, providing a user-friendly interface for interacting with the classifier.
## Usage

-> Upload an image of one of those celebrity via the web app.\
-> The model processes the image, detecting the face and eyes, and then classifies the celebrity.\
-> The predicted celebrity's name is displayed on the web page.\
-> You can also any random person's image and check the similarity of their face to all the models whose faces are trained in the system

## Results

Logistic Regression achieved the highest accuracy with a score of 87% on the test set.\
Confusion matrix and classification report were generated to evaluate the model's performance.