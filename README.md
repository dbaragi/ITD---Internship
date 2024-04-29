# Idaho Transportation Department - Pavement Segregation Project

## Overview

This repository contains the work completed during my internship as a Data Analyst, focusing on the task of pavement segregation.

## Project Description

The objective of this project was to utilize an AI model to detect pavement segregation within images captured from cameras. The project involved analyzing over 200 images and implementing image segmentation techniques to accurately classify pavement segregation.

## Tools and Techniques Used

- **Image Segmentation:** Initially, YOLOv8 was employed for image segmentation to identify pavement segregation within the images.
- **YOLOv8 Implementation:** The YOLOv8 implementation involved training the model on a labeled dataset and fine-tuning it to suit the pavement segregation task.
- **Challenges:** Despite initial attempts with YOLOv8, it became evident that the model's accuracy was compromised due to the nature of some images, leading to inaccurate results.

## Shift to U-Net

Due to the limitations encountered with YOLOv8, a shift was made to another model, U-Net. U-Net is a convolutional neural network (CNN) architecture commonly used for image segmentation tasks. Its ability to accurately segment images, especially in scenarios with less data (as in our case) or complex backgrounds, made it a suitable choice for our project.

## Documentation

The documentation for the work done can be found in ITD_doc.docx
The link for all the python notebooks of training and predictions is: https://drive.google.com/file/d/1rpQgrA996Oo0obOG69Awqtn63JwUagUT/view?usp=share_link
Updates are still being made as expected results are still not obtained.
## Dataset and Annotations

The dataset used for training and annotations were prepared using the CVAT. The annotations generated in CVAT were then utilized for training the YOLOv8 model.

## Data Format for YOLOv8

The dataset used for YOLOv8 training was prepared in the following format:

- **Image Format:** Images in standard image formats (e.g., JPEG, PNG) were used for training.
- **Label Format:** Labels were generated in YOLO format, which consists of text files (.txt) containing bounding box coordinates and class labels for each image.

## Dataset Availability

The dataset used for YOLOv8 training and annotations are available for access via the following link:

[Dataset Link](https://drive.google.com/drive/folders/12HBTPv8cKrgFiW_tKMJUGVo7QHuqf7V_?usp=sharing)

## Conclusion

The transition from YOLOv8 to U-Net was necessitated by the challenges encountered during YOLOv8 implementation. Despite the efforts invested, the limitations of YOLOv8 in handling smaller datasets became apparent. The repository serves as a documentation of the journey, including the experimentation with YOLOv8 and the eventual transition to U-Net for pavement segregation detection.

For any inquiries or feedback, feel free to reach out!
