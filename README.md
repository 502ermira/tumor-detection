# Tumor Detection with Image Processing

This project involves developing an image processing algorithm to automatically detect tumors in MRI images using various image processing techniques in MATLAB.

## Project Overview

This project explores techniques such as filtering, thresholding, and morphological operations to improve the tumor detection algorithm. The successful development of an automated tumor detection algorithm can significantly impact clinical practices, such as improving the accuracy and efficiency of cancer diagnosis and treatment planning.

## Scripts Description

### butterworthHPF.m
Performs high-pass Butterworth filtering to enhance the edges of objects in the image, facilitating tumor detection.

### butterworthLPF.m
Applies low-pass Butterworth filtering to remove high-frequency noise from the image and then detects circular objects which may correspond to tumors.

### medianF.m
Implements median filtering to remove noise while preserving the edges of objects in the image.

### morphology.m
Uses morphological operations such as opening, closing, and reconstruction to process and enhance image structures for better tumor detection.

### thresholdSegmentation.m
Uses thresholding methods to segment the image and differentiate the tumor from the background.

### driver.m
The main script that coordinates the tumor detection process by calling the above methods and displaying the results.

## Results

The algorithm has been tested on a dataset of MRI images. The results show that the combination of filtering, thresholding, and morphological operations can effectively detect tumors. The high-pass Butterworth filter enhances the edges, making it easier to identify the tumor boundaries. The low-pass Butterworth filter helps in identifying circular objects which are potential tumors. Median filtering successfully reduces noise without losing important details. Morphological operations further refine the detected structures, improving the accuracy of tumor detection.

## Usage

The code is free to use and can be adjusted to meet your own needs. Feel free to test and modify it for your specific requirements.

