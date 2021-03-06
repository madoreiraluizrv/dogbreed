### Table of Contents

1. [Project Overview](#overview)
2. [Installation](#installation)
3. [File Descriptions](#files)
4. [How to Run](#how)
5. [Results](#results)
6. [Licensing, Authors, and Acknowledgements](#licensing)

## Project Overview<a name="overview"></a>

In this project, I have built a pipeline to process real-world, user-supplied images, using Convolutional Neural Networks (CNNs).
Given an image of a dog, the algorithm identifies an estimate of the canine’s breed. If supplied an image of a human, the code identifies the resembling dog breed.
This is a Capstone Project of the Udacity Data Scientist Nanodegree, and some of the data inputs used were inside Udacity network (not available here).
The only data inputs I have added were the bottleneck features from Resnet50 pre-trained model (available on bottleneck_features folder) and some images to test the algorithm (availble on the images folder).

## Installation <a name="installation"></a>

There should be no necessary libraries to run the code here beyond the Anaconda distribution of Python and the libraries imported on the Jupyter notebook. 
The code should run with no issues using Python versions 3. However, if you need to know more about the requrements, these are the libraries used (and listed on the requirements folder): opencv-python, h5py, matplotlib, numpy, scipy, tqdm, keras, scikit-learn, pillow, ipykernel and tensorflow-gpu.

## File Descriptions <a name="files"></a>

Every part of the algorithm is available on the dog_app.ipynb notebook.
The only code outside of that file is on extract_bottleneck_features.py, with some functions to extract the bottleneck features of a few varied models.
The other files on the folder are just data: pre-loaded bottlneck features, images to test, saved models.

## How to Run<a name="how"></a>

To run the project, you only need to run each cell of the dog_app.ipynb notebook sequentially.

## Results<a name="results"></a>

The final implementation resulted in 81% of accuracy. I also tested the model with a few images from my computer, with really satisfactory results (as told at the end of the Jupyter notebook.

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Feel free to use the code here as you would like! And if you have any feedback, please share
