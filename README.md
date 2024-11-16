###  Potato Disease Classification
This project utilizes deep learning and computer vision to classify potato leaves as healthy or diseased. Diseased leaves are further categorized into two specific conditions: Early Blight and Late Blight. The project is designed as an end-to-end application, including training the model, deploying it as a backend API, and providing both a web-based and mobile-based frontend for user interaction.

While the core functionalities have been implemented, deployment using Docker and Google Cloud Platform (GCP) is planned but not yet complete.

## Table of Contents

Features
Tech Stack
Backend
Frontend
Mobile App
Model Training
Planned Features
Credits and Inspiration

## Features
Classification Model

Built using Convolutional Neural Networks (CNN).
Classifies images into three categories:
  Healthy
  Early Blight
  Late Blight

Frontend
Web-based Interface: Built with ReactJS to allow users to upload images and view predictions.
Mobile App: A cross-platform application developed in React Native for on-the-go disease classification.

Backend API
Developed using FastAPI, enabling RESTful APIs for inference.
TensorFlow Serving integration for scalable model inference.

Cloud Deployment (Planned)
Dockerized Deployment: Containerize the TensorFlow Serving model for portability and scalability.
GCP Integration: Host models and APIs on Google Cloud for real-world usage.

Model Conversion
TensorFlow Lite model for optimized inference on mobile devices.

## Tech Stack

Machine Learning
Python for data processing and model development.
TensorFlow for deep learning and model training.
Backend
FastAPI for building APIs.
TensorFlow Serving for scalable model serving.
Frontend
ReactJS for the web interface.
React Native for the mobile application.
Mobile App
Built using React Native CLI.
Optimized for Android and iOS.
Development and Deployment Tools
Docker (Planned): For containerization and scalable deployment.
Google Cloud Platform (Planned): For hosting models and APIs.
Jupyter Notebook for prototyping and training workflows.
Postman for testing API endpoints.

## Planned Features
Docker Deployment

Containerize the application for easier deployment and scalability.
Google Cloud Platform (GCP) Deployment

Upload the TensorFlow model to Google Cloud Storage.
Deploy inference logic using Google Cloud Functions.

## Credits and Inspiration
Inspired by the Plant Village dataset available on Kaggle.
https://www.kaggle.com/datasets/arjuntejaswi/plant-village

Deployment strategy inspired by TensorFlow Serving on GCP.
https://cloud.google.com/blog/products/ai-machine-learning/how-to-serve-deep-learning-models-using-tensorflow-2-0-with-cloud-functions
