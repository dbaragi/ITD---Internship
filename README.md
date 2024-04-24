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

## Work Done with YOLOv8

For the YOLOv8 implementation, the following steps were undertaken:

- **Installation of Ultralytics:** The Ultralytics library was installed to facilitate the implementation of YOLOv8.
- **GPU Configuration:** GPU support was configured on the local machine to accelerate training and inference processes.
- **Choice of Editor:** Spyder was utilized as the primary code editor for developing and testing YOLOv8 implementations.
- **Usage of Google Colab:** Google Colab, with its free GPU support, was also utilized for training and experimentation due to its faster processing capabilities.
- **Model Selection:** The pre-trained YOLOv8 model "yolov8n-seg.pt" was chosen for its suitability in pavement segregation tasks.
- **Training Process:** Training was conducted with varying epochs and image sizes. Starting with 3 epochs, the process was gradually increased to 5 and then 10 epochs to observe improvements in results.
- **Observations:** While some visible results were observed with increased epochs, it became apparent that the accuracy of the model was hindered by the limited dataset size. YOLOv8 has specific requirements regarding the size of the dataset for effective training.

## Data Link for YOLOv8 Segmentation

[Data Link](https://drive.google.com/drive/folders/12HBTPv8cKrgFiW_tKMJUGVo7QHuqf7V_?usp=sharing)

## Conclusion

The transition from YOLOv8 to U-Net was necessitated by the challenges encountered during YOLOv8 implementation. Despite the efforts invested, the limitations of YOLOv8 in handling smaller datasets became apparent. The repository serves as a documentation of the journey, including the experimentation with YOLOv8 and the eventual transition to U-Net for pavement segregation detection.

For any inquiries or feedback, feel free to reach out!
