# Senior-Design-2025
### IMPORTANT: THIS README IS STILL BEING UPDATED

## ECE Senior Design, Penn State Behrend
This repository contains the Colab Notebooks and testing results from Landon Grafton concerning the "multiple binary models" solution for Classifying Invasive Species using Drone Images and Deep Learning
- Each notebook begins with the process of mounting a dataset from Microsoft Sharepoint into the Colab instance.
- After the mounting, the dataset is split into training, validation, and testing sets for binary models
- Once the splits are made, training is done using YOLOv11-cls

Throughout training the model to target each individual species, the process and methodology were refined to enhance fluidity and ease-of-use.

## Notes on each training run:
### Run 1
The initial notebook. Only used 100 images from "none" and the "purple_loosestrife" datasets with 10 epochs. This showed a promising start to using YOLOv11 as our model for classification

![Results](/Training_Runs/run1/results.png?raw=true "Results for run1")