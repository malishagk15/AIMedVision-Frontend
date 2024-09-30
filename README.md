# AIMedVision Frontend
This is the frontend for the AIMedVision medical image classifier. It consists of a single index.html file that interacts with the backend REST API to classify medical images for Colon Pathology and Chest X-Ray datasets.

# Features
Allows users to select between two models: Colon Pathology and Chest X-Ray.
Users can upload an image for classification.
The predicted class and label are displayed after the image is processed by the backend API.

# Installation and Usage
Clone the repository and open the index.html file in a web browser.
Ensure the backend Flask server is running at http://127.0.0.1:5000.
Select a model and upload an image for classification.
The prediction result will be displayed on the webpage.

# Requirements
A running instance of the AIMedVision-Backend API.
Browser support for fetch API and file uploads.

# How It Works
The frontend allows users to select a classification model and upload an image.
The image and selected model are sent via POST request to the Flask backend.
The backend processes the image and returns the classification result, which is displayed on the page.
