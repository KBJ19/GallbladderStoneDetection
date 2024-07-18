# Gallbladder Stone Detection Project

## Overview

This project focuses on developing a novel technique for detecting gallbladder stones using ultrasound imaging (USG). Traditional diagnostic practices often rely on expensive MRI and CT scans, posing significant financial burdens. Our proposed method introduces a cost-effective alternative leveraging advanced deep learning techniques.

## Methodology

The project employs a two-step approach:
1. **Gallbladder Identification and ROI Extraction**: Utilizing a region proposal network (RPN) to generate candidate regions of interest (RoIs) from the input USG image.
2. **Classification with Second-Order Pooling Architecture**: Extracting features from RoIs and classifying them using a fully connected layer. A curriculum learning approach inspired by human visual acuity is incorporated to reduce texture biases.

## Key Features
- **Data Source**: The Gallbladder Cancer Ultrasound (GBCU) dataset containing 1255 ultrasound images from 218 patients, including pixel-level annotation masks.
- **Model Performance**: Evaluated using criteria such as accuracy, sensitivity, specificity, F1 score, and AUC.
- **Tools and Technologies**: Developed using Python with deep learning libraries like TensorFlow and PyTorch. The project requires substantial processing power and optional GPU support.

## Results and Impact

Our model demonstrates promising results in surpassing the performance of existing CNN-based models. It not only aims to improve detection accuracy but also offers a more accessible and affordable diagnostic option, potentially transforming current medical practices.

## Future Work

Future enhancements include:
- Extensive clinical validation through collaboration with medical experts.
- Integration into clinical workflows with user-friendly interfaces.
- Exploration of additional imaging modalities.
- Addressing regulatory and ethical considerations for deployment in healthcare settings.
- Conducting longitudinal studies to assess long-term performance.
- Expanding the model's application to other medical domains.

## Acknowledgments

We express our sincere gratitude to Prof. Grishma Sharma for her expert guidance and the Somaiya Vidyavihar University's Department of Computer Engineering for their support. We also thank the GBC-IITD research group for providing the GBCU dataset.

## Model Architecture 

## VGG16

![image](https://github.com/user-attachments/assets/ff74d63f-1fc7-40f2-9842-e248a5e6f8e1)

## ResNet50

![image](https://github.com/user-attachments/assets/7f0d9a10-c83d-41b7-8c4c-a87f3620d8b1)

## MobileNetV2

![image](https://github.com/user-attachments/assets/a958ef41-dfdd-4b65-a36a-316938052cbe)


## Approuch 

## Curriculum Learning

![image](https://github.com/user-attachments/assets/18289e89-f89a-4024-84cd-94e777038847)

## Pooling Architecture

![image](https://github.com/user-attachments/assets/39ea0b29-79a0-44e3-8c70-7e9cfdb9f3c0)


## Results

![image](https://github.com/user-attachments/assets/a3dde7f7-de36-4cf4-bc6b-ae641f87049c)

![image](https://github.com/user-attachments/assets/14802736-455a-4f7b-9fdf-da244a4df351)









