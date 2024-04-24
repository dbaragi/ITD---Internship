# Idaho Transportation Department - Pavement Segregation Project

## Overview

This repository contains the work completed during my internship as a Data Analyst, focusing on the task of pavement segregation.

## Project Description

TThe objective of this project was to utilize an AI model to detect pavement segregation within images captured from cameras. The project involved analyzing over 200 images and implementing image segmentation techniques to accurately classify pavement segregation.

## Tools and Techniques Used

- **Image Segmentation:** Initially, YOLOv8 was employed for image segmentation to identify pavement segregation within the images.
- **YOLOv8 Implementation:** The YOLOv8 implementation involved training the model on a labeled dataset and fine-tuning it to suit the pavement segregation task.
- **Challenges:** Despite initial attempts with YOLOv8, it became evident that the model's accuracy was compromised due to the nature of some images, leading to inaccurate results.

## Shift to U-Net

Due to the limitations encountered with YOLOv8, a shift was made to another model, U-Net. U-Net is a convolutional neural network (CNN) architecture commonly used for image segmentation tasks. Its ability to accurately segment images, especially in scenarios with less data (as in our case) or complex backgrounds, made it a suitable choice for our project.



## Conclusion

Despite encountering challenges with the initial model choice, the project successfully transitioned to U-Net, resulting in improved accuracy and reliability in pavement segregation. The repository serves as a comprehensive resource documenting the journey and outcomes of the internship project.

For any inquiries or feedback, feel free to reach out!


Data Link for yolo-v8 segmentation: https://drive.google.com/drive/folders/12HBTPv8cKrgFiW_tKMJUGVo7QHuqf7V_?usp=sharing
