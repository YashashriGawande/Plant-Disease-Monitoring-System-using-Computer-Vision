# Tomato-Leaf-Disease-Detection-Major-Project

# Introduction

Plant disease detection plays an important role in the agriculture field, as having a disease in plants are quite natural. If proper care is not taken in this area then it can cause serious effects on plants and due to which respective product quality and productivity is also affected.
Plant diseases cause a periodic outbreak of diseases which leads to large-scale death. These problems need to be solved at the initial stage, to save life and money of people. The goal is to develop a system that can accurately identify and classify different plant diseases from images of plants. Overall, the project aims to help farmers and growers identify plant diseases early on and take appropriate measures to prevent or treat them, thereby improving crop yield and reducing economic losses.


# System Implementation

The project will involves following steps: 

1. Collecting a large dataset of images of healthy and diseased plants representing different species.
2. Pre-processing the images to remove noise, normalize lighting and improve contrast.
3. Extracting features from the plant images using convolutional neural networks (CNN).
4. Building and training a machine learning model to classify different plant diseases.
5. Evaluating the accuracy of the model on a validation dataset and optimizing the model for better performance.


## Working

In the initial step, the images of all the leaf samples were picked up.
The step-by-step procedure of the proposed system:

+ RGB image acquisition;
+ Masking the green-pixels;
+ Removal of masked green pixels;
+ Segment the components;
+ Obtain useful segments;
+ Evaluating feature parameters for classification;
