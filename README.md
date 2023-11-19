# Latin Manuscript Paragraph Detection 

This project focuses on detecting paragraphs in Latin manuscripts using the Detectron2 framework. The goal is to train a Faster R-CNN model on a dataset of Latin manuscript images to accurately identify and delineate paragraphs, as seen below. 

![Amphelisa-06v (1)](https://github.com/nikitab7/manuscript-detection/assets/106767139/4aaaeba5-bbcd-43e3-917c-42dea385e949)


## Setup
Before running the code, ensure you have the required libraries installed. The code snippet includes the necessary setup, such as importing libraries, configuring the logger, and setting up common utilities.

## Data Visualization
The code includes a visualization step where it randomly selects two examples from the dataset and displays them using the Detectron2 Visualizer. This allows users to inspect how the model performs on sample images.

## Model Configuration
The Faster R-CNN model is configured using the COCO-Detection/faster_rcnn_R_50_DC5_1x.yaml configuration file from the Detectron2 model zoo. The training parameters, such as batch size, learning rate, and the number of iterations, are set to reasonable values for this specific task.
