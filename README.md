# Pre-trained-Image-Classifier-to-Identify-Dog-Breeds
This repository contains _REVISED_ code and associated files for the AI Programming with Python Nanodegree program. This repository consists of a number of tutorial notebooks for various coding exercises and programming labs that will be used to supplement the lessons of the course.

### Programming Project
* [Intro to Python Project - Classifying Pet Images:](https://github.com/udacity/AIPND-revision/tree/master/intropyproject-classify-pet-images "Classifying Pet Images Project") Determine which CNN architecture model works best at classifying images of dogs and their breeds.

### Running the programm
The "main()" function is located at "check_images.py"
Three arguments are passed by default:
  - directory: "--dir uploaded_images/".
  - model architecture: "--arch vgg".
  - text file containing all the dognames(breeds): "--dogfile dognames.txt", in order to compare it to the classifier.

Example:

  "python check_images.py --dir uploaded_images/ --arch vgg  --dogfile dognames.txt > vgg_uploaded-images.txt"
