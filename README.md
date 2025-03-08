Hand Gesture Classification Using MediaPipe & HaGRID Dataset

Overview

This project focuses on classifying hand gestures using landmark data extracted with MediaPipe from the HaGRID (Hand Gesture Recognition Image Dataset). The dataset consists of 18 hand gesture classes, and the goal is to train a machine learning model for accurate classification.

Features

Data Preprocessing: Cleaning and normalizing landmark coordinates.

Visualization: Plotting keypoints and analyzing class distribution.

Model Training: Implementing and comparing Random Forest, SVM, and KNN models.

Evaluation: Reporting accuracy, precision, recall, and F1-score.

Live Gesture Recognition: Using OpenCV and MediaPipe to process video input.

Dataset

The dataset consists of 21 hand landmarks (x, y, z coordinates). These landmarks are extracted using MediaPipe Hands and stored in a CSV file along with corresponding gesture labels.

Installation

To run this project, install the required dependencies:
pip install numpy pandas scikit-learn matplotlib seaborn mediapipe opencv-python

Usage

Prepare Data: Place the CSV file containing landmark data in the project directory.

Run Training: Execute the Python script to train and evaluate the models.

Prediction: Use the trained model to classify hand gestures from a video.

Results

Best Model: The model with the highest accuracy is selected automatically.

Evaluation Metrics: Precision, recall, and F1-score are displayed for each model.

Video Demo: A hand gesture recognition system.

Project Structure

├── hand_gesture_classification.ipynb  # Main script

├── README.md  # Project documentation

Contributing
Feel free to fork this repository, report issues, or contribute improvements!

License
This project is open-source under the MIT License.

 
