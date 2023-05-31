# PBL-Project
# Sign language Recognition Project

# Image_collection : 
This module is used to create dataset. This code captures images from a webcam and 
saves them into labeled folders, using OpenCV and creating a directory for each label.

# Rename_convert : 
This module renames image files in a given folder by adding a prefix and a numeric 
counter to the filenames. It iterates through the files, checks if they have image extensions, constructs new 
filenames, and renames the files accordingly. It also takes image files from the input directory, converts 
them to grayscale, resizes them to 49x49 pixels, and saves the resized grayscale images in the output 
directory.

# Model_Training :
This module creates and trains a CNN model using TensorFlow and Keras for image 
classification. It utilizes data generators for preprocessing images, defines the model architecture with 
convolutional and fully connected layers, and saves the trained model. The images should be grayscale 
and organized into separate directories for training and validation.

# Sign_Read : 
This code uses a pre-trained sign recognition model to classify hand signs captured from a
video stream. It detects the hand region, resizes it to 49x49 pixels, performs prediction using the model, 
and displays the predicted sign label on the video stream in real-time.
