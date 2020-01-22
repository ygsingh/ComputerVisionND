# Computer Vision Nanodegree

This program is designed to enhance your existing machine learning and deep learning skills with the addition of computer vision theory and programming techniques. These computer vision skills can be applied to various applications such as image and video processing, autonomous vehicle navigation, medical diagnostics, smartphone apps, and much more. This is the repository of my exercises and projects for this nanodegree.

## Reference Material
- Code exercises and materials for Udacity's Computer Vision Nanodegree program is available [here](https://github.com/udacity/CVND_Exercises).
- Notebooks for learning about object motion and localization methods in the last section of CVND are available [here](https://github.com/udacity/CVND_Localization_Exercises)

## Course 1: Introduction to Computer Vision

- Lesson 1:  Introduction to Computer Vision
- Lesson 2: Image Representation and Analysis
- Lesson 3: Convolutional NN Layers
- Lesson 4: Features and Object Recogition
- Lesson 5: Image Segmentation

### Project 1: Facial Keypoint Detection
Use image processing techniques and deep learning techniques to detect faces in an image and find facial keypoints, such as the position of the eyes, nose, and mouth on a face.

## Course 2: Advanced Computer Vision and Deep Learning

- Lesson 1: Advanced CNN Architectures
- Lesson 2: Recurrent Neural Networks
- Lesson 3: Attention Mechanisms
- Lesson 4: Image Captioning

### Project 2: Automatic Image Captioning
Combine CNN and RNN knowledge to build a deep learning model that produces captions given an input image.

## Course 3: Object Tracking and Localization

- Lesson 1: Object Motion and Tracking
- Lesson 2: Optical Flow and Feature Matching
- Lesson 3: Robot Localization
- Lesson 4: Graph SLAM

### Project 3: Landmark Detection and Tracking
Use feature detection and keypoint descriptors to build a map of the environment with SLAM (simultaneous localization and mapping). Implement a robust method for tracking an object over time, using elements of probability, motion models, and linear algebra.

## Exercises

* [Image Representation & Classification](exercises/1_1_Image_Representation) - In this exercise, I learn how images are represented numerically and implement image processing techniques, such as color masking and binary classification.
* [Convolutional Filters and Edge Detection](exercises/1_2_Convolutional_Filters_Edge_Detection) - In this exercise, I learn about frequency in images and implement my own image filters for detecting edges and shapes in an image. Use Haar cascade classifiers from the OpenCV library to perform face detection.
* [Types of Features & Image Segmentation](exercises/1_3_Types_of_Features_Image_Segmentation) - In this exercise, I program a corner detector and learn techniques, like k-means clustering, for segmenting an image into unique parts.
* [Feature Vectors](exercises/1_4_Feature_Vectors) - In this exercise, I learn how to describe objects and images using feature vectors (ORB, FAST, BRIEF, HOG).
* [CNN Layers and Feature Visualization](exercises/1_5_CNN_Layers) - In this exercise, I define and train my own convolution neural network for clothing recognition. Learn to use feature visualization techniques to see what the network had learned.
* [YOLO](exercises/2_2_YOLO) - In this exercise, I learn about the YOLO (You Only Look Once) multi-object detection model and work with a YOLO implementation. Implement YOLO to work with my webcam.
* [LSTMs](exercises/2_4_LSTMs) - In this exercise, I learn about Long Short-Term Memory Networks (LSTM), and similar architectures which have the benefits of preserving long-term memory. Implement a Character-Level LSTM model.
* [Attention Mechanisms](exercises/2_6_Attention) -  Todo.

##  Localization Exercises

* [Optical Flow](localization_exercises/4_1_Optical_Flow) - In this exercise, I learn about and implement Optical Flow.
* [Robot Localization](localization_exercises/4_2_Robot_Localization) - In this exercise, I learn how to implement a Bayesian filter to locate a robot in space and represent uncertainty in robot motion.
* [Mini-project: 2D Histogram Filter](localization_exercises/4_3_2D_Histogram_Filter) - In this exercise, I write sense and move functions for a (and debug) 2D histogram filter.
* [Introduction to Kalman Filters](localization_exercises/4_4_Kalman_Filters) - In this exercise, I learn the intuition behind the Kalman Filter, a vehicle tracking algorithm, and implement a one-dimensional tracker.
* [Representing State and Motion](localization_exercises/4_5_State_and_Motion) - In this exercise, I learn to represent the state of a car in a vector that can be modified using linear algebra.
* [Matrices and Transformation of State](localization_exercises/4_6_Matrices_and_Transformation_of_State) - In this exercise, I learn about the matrix operations that underly multidimensional Kalman Filters.
* [Simultaneous Localization and Mapping (SLAM)](localization_exercises/4_7_SLAM) - In this exercise, I learn how to implement SLAM: simultaneously localize an autonomous vehicle and create a map of landmarks in an environment.
* [Vehicle Motion and Calculus](localization_exercises/4_8_Vehicle_Motion_and_Calculus) - In this exercise, I review some basic calculus and learn how to derive the x and y components of a self-driving car's motion from sensor measurements and other data.
