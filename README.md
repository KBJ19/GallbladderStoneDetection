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

